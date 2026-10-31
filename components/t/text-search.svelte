<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/f/flda0ybka.css';
import '../../css/e/etcm3bbvq.css';
import '../../css/k/kh3r6ssqc.css';
import '../../css/w/wwsea4b-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="flda0ybka wm-shadow"/><path class="etcm3bbvq wm-shadow"/><path class="kh3r6ssqc"/><path class="wwsea4b-l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:text-search" {...props}></Icon>
