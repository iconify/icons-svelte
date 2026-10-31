<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dkv48acbf.css';
import '../../css/o/o0ihmsbgn.css';
import '../../css/s/sc6l7vb1a.css';
import '../../css/o/oki_akbvh.css';
import '../../css/r/rh9qoibkn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dkv48acbf"><path class="o0ihmsbgn"/><path class="sc6l7vb1a"/><path class="oki_akbvh"/><path class="rh9qoibkn wm-deco"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-kawaii:wifi-low" {...props}></Icon>
