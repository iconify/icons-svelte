<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/g/gpuvf8bwr.css';
import '../../css/o/o-tsjlamj.css';
import '../../css/m/m9avzl1wk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="gpuvf8bwr wm-deco"/><path class="o-tsjlamj wm-deco"/><path class="m9avzl1wk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:voicemail-blueprint" {...props}></Icon>
