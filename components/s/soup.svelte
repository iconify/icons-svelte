<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wup9xabdg.css';
import '../../css/w/wlwgd_xcs.css';
import '../../css/d/d84faeanp.css';
import '../../css/h/hyiuzhbmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wm-a wup9xabdg"/><path class="wlwgd_xcs wm-a"/><path class="d84faeanp wm-k"/><path class="hyiuzhbmd wm-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:soup" {...props}></Icon>
