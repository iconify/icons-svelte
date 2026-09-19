<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/o3kywkbui.css';
import '../../css/w/w05e6sayd.css';
import '../../css/j/j-woxn_pq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="o3kywkbui"/><path class="w05e6sayd"/><path class="j-woxn_pq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:scissors" {...props}></Icon>
