<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ef6q_cc6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ef6q_cc6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:trebuchet" {...props}></Icon>
