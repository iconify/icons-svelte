<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/og78ukbbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="og78ukbbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:warning-box" {...props}></Icon>
