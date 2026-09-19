<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jkvak3bev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="jkvak3bev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:voicemail" {...props}></Icon>
