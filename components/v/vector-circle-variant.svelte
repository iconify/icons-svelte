<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xculh0bsl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xculh0bsl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:vector-circle-variant" {...props}></Icon>
