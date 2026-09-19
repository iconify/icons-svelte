<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/t/tq-z5t1rp.css';
import '../../css/j/jgnk0_ecg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="tq-z5t1rp"/><path clip-rule="evenodd" class="jgnk0_ecg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:search-loading" {...props}></Icon>
