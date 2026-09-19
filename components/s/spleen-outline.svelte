<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/e/eqquj7bkg.css';
import '../../css/g/gi4z11bdi.css';
import '../../css/i/icynqdbqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="eqquj7bkg"/><path class="gi4z11bdi"/><path class="icynqdbqy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:spleen-outline" {...props}></Icon>
