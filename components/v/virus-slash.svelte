<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3w--zbbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="z3w--zbbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:virus-slash" {...props}></Icon>
