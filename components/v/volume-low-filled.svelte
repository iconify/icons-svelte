<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/np5mjvb_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="np5mjvb_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:volume-low-filled" {...props}></Icon>
