<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/x/xzf6s-m2d.css';
import '../../css/a/a5x-1hbqo.css';
import '../../css/f/f8rvuy2ad.css';
import '../../css/x/xrgx2dblx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="xzf6s-m2d"/><path class="a5x-1hbqo"/><path class="f8rvuy2ad"/><path class="xrgx2dblx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:stopwatch-circle" {...props}></Icon>
