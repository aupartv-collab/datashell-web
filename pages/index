import Head from 'next/head';

export default function Home() {
  return (
    <div className="bg-slate-50 min-h-screen font-sans">
      <Head>
        <title>Datashell | Consultoría Tecnológica y Estándares ISO</title>
        <meta name="description" content="Líderes en implementación de ISO 27001, 20000 y Ciberseguridad en México." />
      </Head>

      {/* Hero Section - Impacto Inmediato */}
      <nav className="p-6 flex justify-between items-center bg-white shadow-sm">
        <div className="text-2xl font-bold text-blue-900">DATASHELL</div>
        <div className="space-x-6 hidden md:block">
          <a href="#servicios" className="hover:text-blue-600">Servicios</a>
          <a href="#auditoria" className="hover:text-blue-600">Auditoría</a>
          <button className="bg-blue-700 text-white px-5 py-2 rounded-lg hover:bg-blue-800 transition">
            Contactar Experto
          </button>
        </div>
      </nav>

      <main className="max-w-6xl mx-auto px-6 py-20">
        <section className="text-center">
          <h1 className="text-5xl md:text-6xl font-extrabold text-slate-900 mb-6">
            Aseguramos la <span className="text-blue-700">Continuidad</span> de su Negocio.
          </h1>
          <p className="text-xl text-slate-600 mb-10 max-w-2xl mx-auto">
            Especialistas en cumplimiento normativo, ciberseguridad y gestión de servicios bajo estándares internacionales.
          </p>
          <div className="flex justify-center gap-4">
            <button className="bg-slate-900 text-white px-8 py-4 rounded-xl font-semibold shadow-lg">
              Ver Soluciones
            </button>
            <button className="border-2 border-slate-300 px-8 py-4 rounded-xl font-semibold">
              Casos de Éxito
            </button>
          </div>
        </section>

        {/* Sección de Puntos de Dolor Resueltos */}
        <section id="servicios" className="mt-32 grid md:grid-cols-3 gap-8">
          {[
            { t: 'Seguridad ISO 27001', d: 'Blindamos su activo más valioso: la información.' },
            { t: 'Gestión ITIL/ISO 20000', d: 'Eficiencia operativa garantizada en sus servicios de TI.' },
            { t: 'Cumplimiento AI 42001', d: 'Gobernanza ética y técnica para Inteligencia Artificial.' }
          ].map((item, i) => (
            <div key={i} className="bg-white p-8 rounded-2xl shadow-sm border border-slate-100 hover:border-blue-300 transition">
              <h3 className="text-xl font-bold mb-3">{item.t}</h3>
              <p className="text-slate-500">{item.d}</p>
            </div>
          ))}
        </section>
      </main>
    </div>
  );
}
