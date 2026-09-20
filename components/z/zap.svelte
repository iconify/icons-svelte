<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ny7g-0bqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ny7g-0bqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:zap" {...props}></Icon>
