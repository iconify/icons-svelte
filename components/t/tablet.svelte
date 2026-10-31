<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/i/i_8b8dbbp.css';
import '../../css/w/wtgv0tbad.css';
import '../../css/l/l9yga1h-l.css';
import '../../css/p/piwvb9bmf.css';
import '../../css/y/yev8gbc7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="i_8b8dbbp wm-shadow"/><path class="wm-shadow wtgv0tbad"/><path class="l9yga1h-l"/><path class="piwvb9bmf"/><path class="yev8gbc7e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:tablet" {...props}></Icon>
