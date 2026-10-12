<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lr5ofoi5l.css';
import '../../css/u/u0d4ys4cz.css';
import '../../css/g/goaubd3xt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="lr5ofoi5l"/><path class="u0d4ys4cz"/><path class="goaubd3xt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:syringe-48-bold" {...props}></Icon>
