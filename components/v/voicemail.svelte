<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/a/amzs2vygw.css';
import '../../css/f/fgl7d3b2i.css';
import '../../css/q/qj2ybmbte.css';
import '../../css/u/uqwdcjxkk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="amzs2vygw wm-shadow"/><path class="fgl7d3b2i wm-shadow"/><path class="qj2ybmbte"/><path class="uqwdcjxkk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:voicemail" {...props}></Icon>
