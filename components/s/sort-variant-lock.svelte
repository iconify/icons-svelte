<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xmi8cmbei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xmi8cmbei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:sort-variant-lock" {...props}></Icon>
