<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r7_rhsbzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r7_rhsbzl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:wifi-low" {...props}></Icon>
