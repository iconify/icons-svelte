<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/hsi9apijf.css';
import '../../css/b/b0xtd884y.css';
import '../../css/j/jm47mgbht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="hsi9apijf"/><path class="b0xtd884y"/><path clip-rule="evenodd" class="jm47mgbht"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:send-clock" {...props}></Icon>
