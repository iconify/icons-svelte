<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vdzbz_bew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vdzbz_bew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:telephone-forward" {...props}></Icon>
