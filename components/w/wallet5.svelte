<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/p/pvl6bvbyg.css';
import '../../css/u/uu4o2hbdh.css';
import '../../css/a/aty_qzhdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pvl6bvbyg"/><path class="uu4o2hbdh"/><path class="aty_qzhdh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:wallet5" {...props}></Icon>
