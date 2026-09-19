<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/m/mq9irnbcc.css';
import '../../css/h/hgpkc4b0w.css';
import '../../css/k/kniikcc3w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mq9irnbcc"/><path class="hgpkc4b0w"/><path class="kniikcc3w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="covid:transmission-virus-handshake" {...props}></Icon>
