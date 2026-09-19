<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n06l587ft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="n06l587ft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:schlix" {...props}></Icon>
