<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tpuw_nboq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tpuw_nboq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:windsock" {...props}></Icon>
