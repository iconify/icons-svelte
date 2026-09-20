<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/og-t-ob6a.css';
import '../../css/z/zvp4gxblo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="og-t-ob6a"/><path class="zvp4gxblo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:signin" {...props}></Icon>
