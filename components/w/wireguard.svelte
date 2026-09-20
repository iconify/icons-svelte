<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d5htat2ww.css';
import '../../css/t/tiikn06-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<ellipse class="d5htat2ww"/><path class="tiikn06-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:wireguard" {...props}></Icon>
