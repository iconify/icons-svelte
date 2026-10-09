<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mdfpjmbun.css';
import '../../css/t/t8mju9b8g.css';
import '../../css/f/f7uhapy5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mdfpjmbun"/><path class="t8mju9b8g"/><path class="f7uhapy5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:screw-20" {...props}></Icon>
