<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/p/prwmzh75z.css';
import '../../css/a/ayhs6pbko.css';
import '../../css/l/l7ckfcc9c.css';
import '../../css/i/iqyqpg9id.css';
import '../../css/s/s53tgbb5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="prwmzh75z wm-deco"/><path class="ayhs6pbko wm-deco"/><path class="l7ckfcc9c wm-k"/><path class="iqyqpg9id wm-k"/><path class="s53tgbb5w wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:split-blueprint" {...props}></Icon>
