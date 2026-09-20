<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/z/z9edi6b_u.css';
import '../../css/k/kd06ylh6g.css';
import '../../css/e/einsz8zxl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="n1lsf0bnc"><circle class="z9edi6b_u"/><circle class="kd06ylh6g"/><circle class="einsz8zxl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:status-preparing-borderless" {...props}></Icon>
