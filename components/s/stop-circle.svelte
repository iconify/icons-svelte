<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mibjjgjza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mibjjgjza"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:stop-circle" {...props}></Icon>
