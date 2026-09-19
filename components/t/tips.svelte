<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/p/p70jf77ka.css';
import '../../css/k/k28phwblq.css';
import '../../css/p/p6znq_gmt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="p70jf77ka"/><path class="k28phwblq"/><path class="p6znq_gmt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:tips" {...props}></Icon>
