<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sul7jy1tl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sul7jy1tl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:system-storage-filled" {...props}></Icon>
