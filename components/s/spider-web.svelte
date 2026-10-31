<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/i/i5-20q0_t.css';
import '../../css/r/rdktr3xsg.css';
import '../../css/f/f61_c6nui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="i5-20q0_t wm-shadow"/><path class="rdktr3xsg wm-shadow"/><path class="f61_c6nui"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:spider-web" {...props}></Icon>
