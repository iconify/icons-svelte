<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wgn4dacid.css';
import '../../css/z/zvp4gxblo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wgn4dacid"/><path class="zvp4gxblo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:signin-duotone" {...props}></Icon>
