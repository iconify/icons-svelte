<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b74gpab8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b74gpab8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:sun" {...props}></Icon>
