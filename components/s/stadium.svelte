<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eiqcs5z8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eiqcs5z8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:stadium" {...props}></Icon>
