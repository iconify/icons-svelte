<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yboxb49-l.css';
import '../../css/p/pbutksb1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yboxb49-l"/><path class="pbutksb1b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:snapchat-square" {...props}></Icon>
