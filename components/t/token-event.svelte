<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tir7etguw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tir7etguw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:token-event" {...props}></Icon>
