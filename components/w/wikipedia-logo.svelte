<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lmo9ppb1i.css';
import '../../css/d/die78ntcw.css';
import '../../css/d/d19l9rbzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="lmo9ppb1i"><path class="die78ntcw"/><path class="d19l9rbzt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate-color:wikipedia-logo" {...props}></Icon>
