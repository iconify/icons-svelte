<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mije3dbds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mije3dbds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:worker-outline" {...props}></Icon>
