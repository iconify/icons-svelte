<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eu--urbsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eu--urbsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:vector-square-fill-round" {...props}></Icon>
