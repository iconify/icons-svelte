<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i7baw6bnm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="i7baw6bnm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:translation-created-stroke-12" {...props}></Icon>
