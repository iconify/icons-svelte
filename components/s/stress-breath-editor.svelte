<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jy3p094dk.css';
import '../../css/j/j_7wf_9wv.css';
import '../../css/d/dk5jy9x_q.css';
import '../../css/m/mf_n5zbhj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jy3p094dk"/><path class="j_7wf_9wv"/><path class="dk5jy9x_q"/><path class="mf_n5zbhj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:stress-breath-editor" {...props}></Icon>
