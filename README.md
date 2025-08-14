<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tabla Comparativa de Alquiler de Vehículos 4x4</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f8fafc;
        }
        /* --- Colores Corporativos --- */
        /* Localiza */
        .localiza-green-dark { background-color: #05662B; }
        .text-localiza-green-dark { color: #05662B; }
        .highlight-localiza { border-left: 4px solid #7DDE21; }

        /* Always */
        .always-blue { background-color: #0284c7; } /* sky-600 */
        .text-always-blue { color: #0369a1; } /* sky-700 */

        /* Dubrovnik */
        .dubrovnik-orange { background-color: #f97316; } /* orange-500 */
        .text-dubrovnik-orange { color: #ea580c; } /* orange-600 */
    </style>
</head>
<body class="p-4 sm:p-6 md:p-8">
    <div class="max-w-7xl mx-auto">
        <header class="mb-8 text-center">
            <h1 class="text-3xl sm:text-4xl font-bold text-gray-800">Tabla Comparativa de Alquiler de Vehículos 4x4</h1>
            <p class="mt-2 text-lg text-gray-600">Análisis de cotizaciones de <span class="font-semibold text-localiza-green-dark">Localiza</span>, <span class="font-semibold text-always-blue">Always</span> y <span class="font-semibold text-dubrovnik-orange">Dubrovnik</span>.</p>
        </header>

        <!-- Contenedor de la tabla con scroll horizontal en móviles -->
        <div class="overflow-x-auto bg-white rounded-xl shadow-lg">
            <table class="w-full text-sm text-left text-gray-700">
                <thead class="text-xs text-white uppercase">
                    <tr>
                        <th scope="col" class="px-6 py-4 bg-gray-700 rounded-tl-xl">Característica</th>
                        <th scope="col" class="px-6 py-4 text-center localiza-green-dark">Localiza (Anual)</th>
                        <th scope="col" class="px-6 py-4 text-center localiza-green-dark">Localiza (Semestral)</th>
                        <th scope="col" class="px-6 py-4 text-center always-blue">Always (12 meses)</th>
                        <th scope="col" class="px-6 py-4 text-center always-blue">Always (6 meses)</th>
                        <th scope="col" class="px-6 py-4 text-center always-blue">Always (1 mes)</th>
                        <th scope="col" class="px-6 py-4 text-center dubrovnik-orange rounded-tr-xl">Dubrovnik</th>
                    </tr>
                </thead>
                <tbody>
                    <!-- Fila de Vehículo -->
                    <tr class="bg-white border-b hover:bg-gray-50">
                        <th scope="row" class="px-6 py-4 font-bold text-gray-900 whitespace-nowrap">Vehículo</th>
                        <td class="px-6 py-4 text-center">Nissan Frontier, S10 o similar</td>
                        <td class="px-6 py-4 text-center">Nissan Frontier, S10 o similar</td>
                        <td class="px-6 py-4 text-center">Toyota Hilux DX o similar</td>
                        <td class="px-6 py-4 text-center">Toyota Hilux DX o similar</td>
                        <td class="px-6 py-4 text-center">Toyota Hilux DX o similar</td>
                        <td class="px-6 py-4 text-center">Toyota Hilux / VW Amarok</td>
                    </tr>
                    <!-- Fila de Plazo -->
                    <tr class="bg-white border-b hover:bg-gray-50">
                        <th scope="row" class="px-6 py-4 font-bold text-gray-900 whitespace-nowrap">Plazo</th>
                        <td class="px-6 py-4 text-center">12 meses</td>
                        <td class="px-6 py-4 text-center">6 meses</td>
                        <td class="px-6 py-4 text-center">12 meses</td>
                        <td class="px-6 py-4 text-center">6 meses</td>
                        <td class="px-6 py-4 text-center">1 mes</td>
                        <td class="px-6 py-4 text-center">21/30 días</td>
                    </tr>
                    <!-- Fila de Valor Mensual -->
                    <tr class="bg-gray-50 border-b hover:bg-gray-100">
                        <th scope="row" class="px-6 py-4 font-bold text-gray-900 whitespace-nowrap">Valor Mensual (sin IVA)</th>
                        <td class="px-6 py-4 text-center font-semibold">$2.270.000</td>
                        <td class="px-6 py-4 text-center font-semibold">$2.500.000</td>
                        <td class="px-6 py-4 text-center font-semibold text-always-blue">$2.199.549</td>
                        <td class="px-6 py-4 text-center font-semibold">$2.321.746</td>
                        <td class="px-6 py-4 text-center font-semibold">$2.388.081</td>
                        <td class="px-6 py-4 text-center font-semibold text-dubrovnik-orange">$2.093.825</td>
                    </tr>
                    <!-- Fila de Km Incluidos -->
                    <tr class="bg-white border-b hover:bg-gray-50">
                        <th scope="row" class="px-6 py-4 font-bold text-gray-900 whitespace-nowrap">Km Incluidos</th>
                        <td class="px-6 py-4 text-center">5.000</td>
                        <td class="px-6 py-4 text-center">5.000</td>
                        <td class="px-6 py-4 text-center font-bold text-always-blue">8.000</td>
                        <td class="px-6 py-4 text-center font-bold text-always-blue">8.000</td>
                        <td class="px-6 py-4 text-center font-bold text-always-blue">8.000</td>
                        <td class="px-6 py-4 text-center">5.000</td>
                    </tr>
                    <!-- Fila de Costo Km Excedente -->
                    <tr class="bg-white border-b hover:bg-gray-50">
                        <th scope="row" class="px-6 py-4 font-bold text-gray-900 whitespace-nowrap">Costo Km Excedente</th>
                        <td class="px-6 py-4 text-center text-gray-500">N/E</td>
                        <td class="px-6 py-4 text-center text-gray-500">N/E</td>
                        <td class="px-6 py-4 text-center">$527,89</td>
                        <td class="px-6 py-4 text-center">$557,22</td>
                        <td class="px-6 py-4 text-center">$573,14</td>
                        <td class="px-6 py-4 text-center font-bold text-green-600">$418,76 + IVA</td>
                    </tr>
                    <!-- Fila de Seguro -->
                    <tr class="bg-gray-50 border-b hover:bg-gray-100">
                        <th scope="row" class="px-6 py-4 font-bold text-gray-900 whitespace-nowrap">Seguro</th>
                        <td class="px-6 py-4 text-center font-bold text-localiza-green-dark">Adicional (TR)</td>
                        <td class="px-6 py-4 text-center font-bold text-localiza-green-dark">Adicional (TR)</td>
                        <td class="px-6 py-4 text-center">Terceros Completo</td>
                        <td class="px-6 py-4 text-center">Terceros Completo</td>
                        <td class="px-6 py-4 text-center">Terceros Completo</td>
                        <td class="px-6 py-4 text-center text-red-600">Resp. Civil (No cubre daños propios)</td>
                    </tr>
                    <!-- Fila de Costo Adicional Seguro -->
                    <tr class="bg-white border-b hover:bg-gray-50">
                        <th scope="row" class="px-6 py-4 font-bold text-gray-900 whitespace-nowrap">Costo Adicional Seguro</th>
                        <td class="px-6 py-4 text-center">$297.500</td>
                        <td class="px-6 py-4 text-center">$297.500</td>
                        <td class="px-6 py-4 text-center text-gray-500">Incluido</td>
                        <td class="px-6 py-4 text-center text-gray-500">Incluido</td>
                        <td class="px-6 py-4 text-center text-gray-500">Incluido</td>
                        <td class="px-6 py-4 text-center text-gray-500">N/A</td>
                    </tr>
                    <!-- Fila de Ajuste de Tarifa -->
                     <tr class="bg-white border-b hover:bg-gray-50">
                        <th scope="row" class="px-6 py-4 font-bold text-gray-900 whitespace-nowrap">Ajuste de Tarifa</th>
                        <td class="px-6 py-4 text-center">Trimestral por IPC</td>
                        <td class="px-6 py-4 text-center">Trimestral por IPC</td>
                        <td class="px-6 py-4 text-center">Trimestral por IPC</td>
                        <td class="px-6 py-4 text-center">Trimestral por IPC</td>
                        <td class="px-6 py-4 text-center">Trimestral por IPC</td>
                        <td class="px-6 py-4 text-center text-gray-500">N/E</td>
                    </tr>
                    <!-- Fila de Condiciones de Pago -->
                     <tr class="bg-white border-b hover:bg-gray-50">
                        <th scope="row" class="px-6 py-4 font-bold text-gray-900 whitespace-nowrap">Condiciones de Pago</th>
                        <td class="px-6 py-4 text-center">Firma Carta Oferta</td>
                        <td class="px-6 py-4 text-center">Firma Carta Oferta</td>
                        <td class="px-6 py-4 text-center">Orden de Compra</td>
                        <td class="px-6 py-4 text-center">Orden de Compra</td>
                        <td class="px-6 py-4 text-center">Orden de Compra</td>
                        <td class="px-6 py-4 text-center">Pago Anticipado</td>
                    </tr>
                    <!-- Fila de Vigencia de Oferta -->
                    <tr class="bg-white hover:bg-gray-50">
                        <th scope="row" class="px-6 py-4 font-bold text-gray-900 whitespace-nowrap rounded-bl-xl">Vigencia de Oferta</th>
                        <td class="px-6 py-4 text-center">30 días</td>
                        <td class="px-6 py-4 text-center">30 días</td>
                        <td class="px-6 py-4 text-center">Mes en curso</td>
                        <td class="px-6 py-4 text-center">Mes en curso</td>
                        <td class="px-6 py-4 text-center">Mes en curso</td>
                        <td class="px-6 py-4 text-center rounded-br-xl">7 días</td>
                    </tr>
                </tbody>
            </table>
        </div>

        <!-- Sección de Resumen y Puntos Clave -->
        <div class="mt-8 p-6 bg-white rounded-xl shadow-lg highlight-localiza">
            <h2 class="text-2xl font-bold text-gray-800 mb-4">Resumen y Puntos Clave</h2>
            <ul class="space-y-3 text-gray-700 list-disc list-inside">
                <li><span class="font-semibold">Mejor Precio (Contrato Anual):</span> <span class="font-bold text-always-blue">Always</span> ofrece el precio más competitivo para 12 meses, siendo ligeramente más económico que <span class="font-bold text-localiza-green-dark">Localiza</span>.</li>
                <li><span class="font-semibold">Mejor Precio (Corto Plazo):</span> <span class="font-bold text-dubrovnik-orange">Dubrovnik</span> tiene la tarifa más baja para un período de ~30 días, aunque con limitaciones importantes en el seguro.</li>
                <li><span class="font-semibold">Mayor Kilometraje:</span> <span class="font-bold text-always-blue">Always</span> destaca claramente al ofrecer 8.000 km mensuales en todos sus planes, un 60% más que la competencia.</li>
                <li><span class="font-semibold">Mejor Cobertura de Seguro:</span> <span class="font-bold text-localiza-green-dark">Localiza</span> es la única opción que ofrece un seguro Todo Riesgo (aunque con costo adicional), brindando la máxima tranquilidad. La cobertura de <span class="font-bold text-dubrovnik-orange">Dubrovnik</span> es la más básica y riesgosa.</li>
                <li><span class="font-semibold">Conclusión General:</span> Para contratos a largo plazo, la elección está entre el <span class="font-semibold">precio y kilometraje de <span class="font-bold text-always-blue">Always</span></span> versus la <span class="font-semibold">cobertura superior de <span class="font-bold text-localiza-green-dark">Localiza</span></span>. La decisión final dependerá de si se prioriza el costo operativo o la seguridad total del vehículo.</li>
            </ul>
        </div>
    </div>
</body>
</html>
# josevalencia.github.io