<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lxa1rg38p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lxa1rg38p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:thermometer-high" {...props}></Icon>
