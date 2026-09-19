<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/o/o2jno2buj.css';
import '../../css/i/iru49qbqh.css';
import '../../css/j/jny2pkb_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o2jno2buj"/><path class="iru49qbqh"/><path class="jny2pkb_q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:save-all" {...props}></Icon>
