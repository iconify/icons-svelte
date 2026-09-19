<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-dvm-v0w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n-dvm-v0w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:ruler-combine" {...props}></Icon>
