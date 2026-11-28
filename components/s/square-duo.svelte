<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nlpsal7ej.css';
import '../../css/m/mtg_mtnil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nlpsal7ej secondary"/><path class="mtg_mtnil primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:square-duo" {...props}></Icon>
