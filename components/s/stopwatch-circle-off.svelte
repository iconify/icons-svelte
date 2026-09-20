<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/w/w84oibczi.css';
import '../../css/a/aw4bac3ch.css';
import '../../css/t/tnjkyilll.css';
import '../../css/z/zsuclwbnx.css';
import '../../css/k/kspoj7vnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="w84oibczi"/><path clip-rule="evenodd" class="aw4bac3ch"/><path clip-rule="evenodd" class="tnjkyilll"/><path class="zsuclwbnx"/><path clip-rule="evenodd" class="kspoj7vnd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:stopwatch-circle-off" {...props}></Icon>
