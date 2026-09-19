<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/t/tdyuizbqn.css';
import '../../css/l/l33zoes5a.css';
import '../../css/o/o1u583b9p.css';
import '../../css/e/ezgrq_b8g.css';
import '../../css/y/yxu6vo-xt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="tdyuizbqn"/><circle class="l33zoes5a"/><circle class="o1u583b9p"/><circle class="ezgrq_b8g"/><path class="yxu6vo-xt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:skew" {...props}></Icon>
