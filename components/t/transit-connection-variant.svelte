<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dd8xxabva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dd8xxabva"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:transit-connection-variant" {...props}></Icon>
