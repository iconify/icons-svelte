<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/k/kinr2bcxv.css';
import '../../css/o/o6ht1ib0e.css';
import '../../css/o/ov-gx2brx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="kinr2bcxv"/><path class="o6ht1ib0e"/><path class="ov-gx2brx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:text-quote-duo" {...props}></Icon>
