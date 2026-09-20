<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vg8_r5bqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vg8_r5bqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:solar-panel" {...props}></Icon>
