<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yl2uijbpa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yl2uijbpa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:throne-king" {...props}></Icon>
