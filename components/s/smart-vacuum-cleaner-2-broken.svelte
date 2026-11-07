<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/m/m7ukxtbvq.css';
import '../../css/x/xv6kuw8hw.css';
import '../../css/l/ltt5oydcb.css';
import '../../css/g/gyvy_bjrp.css';
import '../../css/k/ko6o-6b9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="m7ukxtbvq"/><path class="xv6kuw8hw"/><path class="ltt5oydcb"/><path class="gyvy_bjrp"/><path class="ko6o-6b9b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:smart-vacuum-cleaner-2-broken" {...props}></Icon>
