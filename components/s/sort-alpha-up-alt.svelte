<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/gkzrwab8u.css';
import '../../css/d/dat65o4mr.css';
import '../../css/q/qi62twexq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="gkzrwab8u"/><path class="dat65o4mr"/><path class="qi62twexq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:sort-alpha-up-alt" {...props}></Icon>
