<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dd2psoywp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dd2psoywp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:tvk" {...props}></Icon>
