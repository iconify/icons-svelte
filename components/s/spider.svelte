<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/n/n57ixwbvq.css';
import '../../css/s/s1gyzwksf.css';
import '../../css/y/ycrm45b1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n57ixwbvq"/><path class="s1gyzwksf"/><path class="ycrm45b1o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:spider" {...props}></Icon>
