<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/e/ezgrq_b8g.css';
import '../../css/o/ozw_qtvty.css';
import '../../css/l/llj5fwt9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="ezgrq_b8g"/><circle class="ozw_qtvty"/><path class="llj5fwt9w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:scooter-04" {...props}></Icon>
