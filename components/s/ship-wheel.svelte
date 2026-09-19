<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/i/i64-1ebxw.css';
import '../../css/y/ysvgjxbjj.css';
import '../../css/t/tlifriksx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><circle class="i64-1ebxw"/><path class="ysvgjxbjj"/><circle class="tlifriksx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:ship-wheel" {...props}></Icon>
