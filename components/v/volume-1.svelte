<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xpl0q1bzo.css';
import '../../css/y/y0-c0ac4t.css';
import '../../css/d/dd6fl6u9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path clip-rule="evenodd" class="xpl0q1bzo"/><path class="y0-c0ac4t"/><path class="dd6fl6u9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:volume-1" {...props}></Icon>
