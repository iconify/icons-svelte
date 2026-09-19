<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/hs3g8e_uk.css';
import '../../css/k/karkvxbcj.css';
import '../../css/n/n6wegsbky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="hs3g8e_uk"/><path class="karkvxbcj"/><path class="n6wegsbky"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:skin-cancer-outline" {...props}></Icon>
