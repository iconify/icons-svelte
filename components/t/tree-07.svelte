<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/h/hmqkr95yr.css';
import '../../css/c/cxgt2g6hf.css';
import '../../css/t/tiz7iu3-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hmqkr95yr"/><path class="cxgt2g6hf"/><path class="tiz7iu3-y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:tree-07" {...props}></Icon>
