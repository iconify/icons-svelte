<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wtzgfvdyl.css';
import '../../css/f/ff38w-bfl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="wtzgfvdyl"/><path class="ff38w-bfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:translation-deleted-fill-12" {...props}></Icon>
