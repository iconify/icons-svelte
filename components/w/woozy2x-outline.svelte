<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/u4ktaub7o.css';
import '../../css/s/svxw3cbgx.css';
import '../../css/y/yzptmubja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="u4ktaub7o"/><path class="svxw3cbgx"/><path clip-rule="evenodd" class="yzptmubja"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:woozy2x-outline" {...props}></Icon>
