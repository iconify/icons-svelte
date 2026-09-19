<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/ve7t91bkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ve7t91bkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:triton-head" {...props}></Icon>
