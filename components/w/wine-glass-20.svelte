<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u2g-f1blp.css';
import '../../css/w/wut29u08z.css';
import '../../css/x/x1osh-brd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="u2g-f1blp"/><path class="wut29u08z"/><path class="x1osh-brd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wine-glass-20" {...props}></Icon>
