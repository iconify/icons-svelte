<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/y/yht5chb_v.css';
import '../../css/d/d9dqksb9z.css';
import '../../css/o/oe5drjvzo.css';
import '../../css/h/hxq6r5mzm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="yht5chb_v"/><path class="d9dqksb9z"/><path class="oe5drjvzo"/><path class="hxq6r5mzm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:tape-measure" {...props}></Icon>
