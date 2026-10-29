<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iuy1aab-e.css';
import '../../css/k/keh7f8wkw.css';
import '../../css/i/ikwvq7b1d.css';
import '../../css/m/mfb6imouq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iuy1aab-e wm-k"/><path class="keh7f8wkw wm-a"/><path class="ikwvq7b1d wm-k"/><path class="mfb6imouq wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:shopping-cart-plus" {...props}></Icon>
