<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xvem7lbye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xvem7lbye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:sea-creature" {...props}></Icon>
