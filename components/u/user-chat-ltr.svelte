<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uiiytincm.css';
import '../../css/g/g8ll7b7pf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="uiiytincm"/><circle class="g8ll7b7pf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:user-chat-ltr" {...props}></Icon>
