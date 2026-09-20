<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/l/l_3w4tbsp.css';
import '../../css/g/g3amwib_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l_3w4tbsp"/><path class="g3amwib_f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:shield-check" {...props}></Icon>
