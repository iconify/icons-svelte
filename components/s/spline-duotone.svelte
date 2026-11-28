<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wzi-nscmo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary wzi-nscmo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:spline-duotone" {...props}></Icon>
