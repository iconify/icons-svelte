<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yj1ucbbxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yj1ucbbxc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:window-filled" {...props}></Icon>
