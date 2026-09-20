<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qwhra4biw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qwhra4biw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:wine-bottle-and-wine-glass" {...props}></Icon>
