<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/snl_hb.css';
import '../../css/x/x93a4q.css';
import '../../css/b/botfzx.css';
import '../../css/c/cx-from-7px.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVG262Nbd6S"><path class="snl_hb"/><circle class="x93a4q"/></mask></defs><path mask="url(#SVG262Nbd6S)" class="botfzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:switch-off-filled-to-switch-filled-transition" {...props}></Icon>
