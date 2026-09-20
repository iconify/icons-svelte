<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qgjtln_kv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qgjtln_kv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:woozy-face-in-circle-outline" {...props}></Icon>
