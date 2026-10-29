<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vjq-6db1p.css';
import '../../css/s/st7bm40ae.css';
import '../../css/m/mz609cc_k.css';
import '../../css/e/ea6yb7buv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vjq-6db1p wm-a"/><path class="st7bm40ae wm-k"/><path class="mz609cc_k wm-k"/><path class="ea6yb7buv wm-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:tv" {...props}></Icon>
