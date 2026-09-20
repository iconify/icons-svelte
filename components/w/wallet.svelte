<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8oo7gb6g.css';
import '../../css/c/c0sioac0q.css';
import '../../css/l/lqp2b9btq.css';
import '../../css/l/lh2z7ynqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<g class="n8oo7gb6g"><path class="c0sioac0q"/><path class="lqp2b9btq"/><path class="lh2z7ynqy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="marketeq:wallet" {...props}></Icon>
