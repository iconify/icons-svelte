<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hfd9koo4a.css';
import '../../css/v/vl8d-nbty.css';
import '../../css/s/shthbcb5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hfd9koo4a"/><path class="vl8d-nbty"/><path class="shthbcb5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:sort-numeric-alt-up" {...props}></Icon>
