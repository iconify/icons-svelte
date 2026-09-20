<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/take-gb5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="take-gb5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:sourcehut-dark" {...props}></Icon>
