<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wp-qfutxl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wp-qfutxl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:sagittarius" {...props}></Icon>
