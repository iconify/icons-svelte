<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p1ej7hb4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="p1ej7hb4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:vala" {...props}></Icon>
