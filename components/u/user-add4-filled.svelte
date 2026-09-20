<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zdy4ny49e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zdy4ny49e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:user-add4-filled" {...props}></Icon>
