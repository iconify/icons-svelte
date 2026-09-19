<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/bhnl5tocy.css';
import '../../css/n/nsw5-gahy.css';
import '../../css/x/xav8j7y3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="bhnl5tocy"/><path clip-rule="evenodd" class="nsw5-gahy"/><path class="xav8j7y3j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:ventilator-24px" {...props}></Icon>
