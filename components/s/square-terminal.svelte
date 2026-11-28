<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/l/lk2gmgbqk.css';
import '../../css/k/kb53_yb0k.css';
import '../../css/n/n2j9rebrd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="lk2gmgbqk"/><path class="kb53_yb0k"/><path class="n2j9rebrd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:square-terminal" {...props}></Icon>
