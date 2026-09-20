<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-7_-31ex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m-7_-31ex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:stackshare-fill" {...props}></Icon>
