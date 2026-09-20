<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q5vpad8jv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q5vpad8jv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ynab" {...props}></Icon>
