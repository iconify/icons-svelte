<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v0im_gbxt.css';
import '../../css/n/n7miu-b0l.css';
import '../../css/f/fahhi3b_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v0im_gbxt"/><path class="n7miu-b0l"/><path class="fahhi3b_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:snapchat" {...props}></Icon>
