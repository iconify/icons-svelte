<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/h/hq-5njbjh.css';
import '../../css/x/xfy0nnwjl.css';
import '../../css/f/fhy922bbx.css';
import '../../css/w/whvwt4bny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="hq-5njbjh"/><path class="xfy0nnwjl"/><path class="fhy922bbx"/><path class="whvwt4bny"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:suitcase-lines-broken" {...props}></Icon>
