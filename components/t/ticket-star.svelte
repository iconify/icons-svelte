<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zn1isfbbx.css';
import '../../css/d/d_e6qbb_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zn1isfbbx"/><path class="d_e6qbb_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:ticket-star" {...props}></Icon>
