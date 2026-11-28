<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-3o6lbxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l-3o6lbxy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:truck-check" {...props}></Icon>
