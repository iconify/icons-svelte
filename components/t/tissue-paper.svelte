<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/r/rhzqnybfy.css';
import '../../css/x/xwt_qrbis.css';
import '../../css/v/vhzi37bzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="rhzqnybfy"/><path class="xwt_qrbis"/><path class="vhzi37bzf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:tissue-paper" {...props}></Icon>
