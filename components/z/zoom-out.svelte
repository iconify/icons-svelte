<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/abtp8tbmo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="abtp8tbmo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:zoom-out" {...props}></Icon>
