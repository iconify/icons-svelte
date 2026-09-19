<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mt3w_hb-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mt3w_hb-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:sine-wave" {...props}></Icon>
