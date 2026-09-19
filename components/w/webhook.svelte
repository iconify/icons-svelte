<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/j/jhq6xabtd.css';
import '../../css/z/zz0g-cc0d.css';
import '../../css/c/cbw1ke_rt.css';
import '../../css/k/k-pnqznjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="jhq6xabtd"/><path class="zz0g-cc0d"/><path class="cbw1ke_rt"/><path class="k-pnqznjx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:webhook" {...props}></Icon>
