<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/we3tkpbbj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="we3tkpbbj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:school-circle-check" {...props}></Icon>
