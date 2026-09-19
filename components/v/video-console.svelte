<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/q/qnmts8ajg.css';
import '../../css/o/otxwmwbyz.css';
import '../../css/l/lzwe0dohb.css';
import '../../css/i/iybdt-b-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="qnmts8ajg"/><path class="otxwmwbyz"/><path class="lzwe0dohb"/><path class="iybdt-b-w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:video-console" {...props}></Icon>
