<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pxvfs20bi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="pxvfs20bi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:twitch-filled" {...props}></Icon>
