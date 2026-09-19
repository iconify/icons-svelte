<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_2lkqbxb.css';
import '../../css/b/bqgkxtcew.css';
import '../../css/o/oygve5bcg.css';
import '../../css/r/r9cpugb5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="t_2lkqbxb"><path class="bqgkxtcew"/><path class="oygve5bcg"/><path class="r9cpugb5q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:webpack" {...props}></Icon>
