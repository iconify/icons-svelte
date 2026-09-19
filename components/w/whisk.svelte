<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/a/axxphcgys.css';
import '../../css/m/ma-1r2bqx.css';
import '../../css/e/evxn836au.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="axxphcgys"/><path class="ma-1r2bqx"/><path class="evxn836au"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:whisk" {...props}></Icon>
