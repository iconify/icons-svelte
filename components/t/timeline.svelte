<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e599b7bpv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e599b7bpv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:timeline" {...props}></Icon>
