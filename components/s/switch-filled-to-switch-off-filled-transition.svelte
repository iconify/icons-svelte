<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/snl_hb.css';
import '../../css/e/e3x2ay.css';
import '../../css/b/botfzx.css';
import '../../css/c/cx-from-17px.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVGjcmRbbQu"><path class="snl_hb"/><circle class="e3x2ay"/></mask></defs><path mask="url(#SVGjcmRbbQu)" class="botfzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:switch-filled-to-switch-off-filled-transition" {...props}></Icon>
