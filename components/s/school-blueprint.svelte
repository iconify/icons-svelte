<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/r/rcld46bpd.css';
import '../../css/b/bvxg-tnme.css';
import '../../css/c/cf3uzcrzx.css';
import '../../css/z/zcrcpgjjd.css';
import '../../css/v/v2dzgoy5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="rcld46bpd wm-deco"/><path class="bvxg-tnme wm-deco"/><path class="cf3uzcrzx wm-deco"/><path class="zcrcpgjjd"/><path class="v2dzgoy5e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:school-blueprint" {...props}></Icon>
