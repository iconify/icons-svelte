<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/li9yl2xtw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="li9yl2xtw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:whiplash" {...props}></Icon>
