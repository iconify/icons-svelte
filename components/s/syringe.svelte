<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn5eo9bqs.css';
import '../../css/j/jukvyzbzf.css';
import '../../css/p/pqz52nbgj.css';
import '../../css/w/wj4j9kl0g.css';
import '../../css/i/imct4h92g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="jukvyzbzf"/><path class="pqz52nbgj"/><path class="wj4j9kl0g"/><path class="imct4h92g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:syringe" {...props}></Icon>
