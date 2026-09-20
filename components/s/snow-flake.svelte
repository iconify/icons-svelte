<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eul96sbdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eul96sbdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:snow-flake" {...props}></Icon>
