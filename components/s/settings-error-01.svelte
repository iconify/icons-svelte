<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/c/cc0yg-bhd.css';
import '../../css/j/jy51gjgdv.css';
import '../../css/l/ly3xvooyq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="cc0yg-bhd"/><path class="jy51gjgdv"/><path class="ly3xvooyq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:settings-error-01" {...props}></Icon>
