<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wp6gv5bfm.css';
import '../../css/q/ql5n44bqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wp6gv5bfm"/><path class="ql5n44bqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:sword-alt-filled" {...props}></Icon>
