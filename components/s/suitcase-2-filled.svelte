<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/dvzi3lbpc.css';
import '../../css/z/zfoh0m8an.css';
import '../../css/p/ps9o2abca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="dvzi3lbpc"/><path class="zfoh0m8an"/><path class="ps9o2abca"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:suitcase-2-filled" {...props}></Icon>
