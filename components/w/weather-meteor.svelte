<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/amosus9kb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="amosus9kb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:weather-meteor" {...props}></Icon>
