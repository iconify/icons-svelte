<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l04k3h--y.css';
import '../../css/v/v1qrver_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="l04k3h--y"/><path class="v1qrver_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:token-module" {...props}></Icon>
