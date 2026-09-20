<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/e/e57ldqyuj.css';
import '../../css/p/pwbt2qflx.css';
import '../../css/j/jdy6ymapr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="e57ldqyuj"/><circle class="pwbt2qflx"/><rect class="jdy6ymapr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:user-box-light" {...props}></Icon>
