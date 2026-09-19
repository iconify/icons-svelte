<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/itzqobc7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="itzqobc7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:shirt" {...props}></Icon>
