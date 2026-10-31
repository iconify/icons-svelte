<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/w/w0l1u8rdw.css';
import '../../css/h/h7zioyf4u.css';
import '../../css/f/frl_d4bif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="w0l1u8rdw wm-shadow"/><path class="h7zioyf4u wm-shadow"/><path class="frl_d4bif"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:scale" {...props}></Icon>
