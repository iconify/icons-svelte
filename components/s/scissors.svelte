<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flen3tbdj.css';
import '../../css/l/l48-m7blu.css';
import '../../css/c/cyfn_yf1w.css';
import '../../css/a/aitpywbwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="flen3tbdj"><circle class="l48-m7blu"/><circle class="cyfn_yf1w"/><path class="aitpywbwi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codex:scissors" {...props}></Icon>
