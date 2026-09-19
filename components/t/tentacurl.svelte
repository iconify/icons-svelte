<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p7g51zbiy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p7g51zbiy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:tentacurl" {...props}></Icon>
