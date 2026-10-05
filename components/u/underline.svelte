<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn5eo9bqs.css';
import '../../css/q/qr4j9nf2v.css';
import '../../css/w/w-p88obja.css';
import '../../css/n/n2mgyywxx.css';
import '../../css/h/hxgw5ab5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="qr4j9nf2v"/><path class="w-p88obja"/><path class="n2mgyywxx"/><path class="hxgw5ab5p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:underline" {...props}></Icon>
