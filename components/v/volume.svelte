<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xol_1mb-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xol_1mb-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:volume" {...props}></Icon>
