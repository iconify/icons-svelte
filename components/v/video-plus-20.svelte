<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wix0a5bey.css';
import '../../css/c/cdonwobot.css';
import '../../css/y/y4i3220kc.css';
import '../../css/z/zkdyo_ief.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wix0a5bey"/><path class="cdonwobot"/><path class="y4i3220kc"/><path class="zkdyo_ief"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:video-plus-20" {...props}></Icon>
