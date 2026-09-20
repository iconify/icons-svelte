<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/e/e5uzaw6kb.css';
import '../../css/x/xpzro9uft.css';
import '../../css/g/gomzfyb9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="e5uzaw6kb"/><path clip-rule="evenodd" class="xpzro9uft"/><path clip-rule="evenodd" class="gomzfyb9s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:safe-duotone" {...props}></Icon>
