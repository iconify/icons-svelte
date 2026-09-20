<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jxjbrub3m.css';
import '../../css/b/bcedl12ma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jxjbrub3m"/><circle class="bcedl12ma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:user-chat-rtl" {...props}></Icon>
