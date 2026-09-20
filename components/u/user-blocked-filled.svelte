<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zd1tw0gyo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zd1tw0gyo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:user-blocked-filled" {...props}></Icon>
