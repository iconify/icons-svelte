<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mi2bm_30d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mi2bm_30d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:triangle-dashed" {...props}></Icon>
