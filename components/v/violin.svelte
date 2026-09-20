<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tb_p7iblt.css';
import '../../css/j/jmf7y0dun.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/h/h557o4b_c.css';
import '../../css/o/o9afzxb_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="tb_p7iblt"/><path class="jmf7y0dun"/><g class="jn8qy4bru"><path class="h557o4b_c"/><path class="o9afzxb_f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:violin" {...props}></Icon>
