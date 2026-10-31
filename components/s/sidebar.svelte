<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/d/dpdeg3i2t.css';
import '../../css/r/rmf8ov87u.css';
import '../../css/c/cvpr-5bot.css';
import '../../css/u/u5r7-lb8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="dpdeg3i2t wm-shadow"/><path class="rmf8ov87u wm-shadow"/><path class="cvpr-5bot"/><path class="u5r7-lb8t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:sidebar" {...props}></Icon>
