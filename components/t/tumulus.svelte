<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qvium4bpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qvium4bpr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:tumulus" {...props}></Icon>
