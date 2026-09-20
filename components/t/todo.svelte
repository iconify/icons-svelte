<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/z/z8c6tx7ee.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/h2o9ifrhs.css';
import '../../css/q/q_pgsqr-e.css';
import '../../css/n/npobut5oa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<g class="bi12bsetm"><path class="z8c6tx7ee"/><g transform="translate(3 3)" class="cuyn6tgcc"><circle transform="matrix(-1 0 0 1 15 0)" class="h2o9ifrhs"/><circle class="q_pgsqr-e"/><circle class="npobut5oa"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:todo" {...props}></Icon>
