<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ysujvx2kd.css';
import '../../css/q/qtfjj6b3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ysujvx2kd"/><path class="qtfjj6b3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:sticker-square-bold-duotone" {...props}></Icon>
