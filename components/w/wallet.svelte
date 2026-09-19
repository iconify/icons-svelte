<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/l9loqrvgk.css';
import '../../css/t/tmh83rwbo.css';
import '../../css/p/p97oy8mpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":38,"height":32};
const content = `<g class="cuyn6tgcc"><path class="l9loqrvgk"/><path class="tmh83rwbo"/><circle class="p97oy8mpb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="et:wallet" {...props}></Icon>
