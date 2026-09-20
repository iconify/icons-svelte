<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kerqhwbpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kerqhwbpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:wxt" {...props}></Icon>
