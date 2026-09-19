<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/ul-m_mdjs.css';
import '../../css/e/ea0acz-ju.css';
import '../../css/u/u6zkyfsky.css';
import '../../css/v/viuo68bqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="ul-m_mdjs"/><path clip-rule="evenodd" class="ea0acz-ju"/><path class="u6zkyfsky"/><path class="viuo68bqo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:syringe-print" {...props}></Icon>
