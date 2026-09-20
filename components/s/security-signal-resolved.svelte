<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tp-9wf2on.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tp-9wf2on"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:security-signal-resolved" {...props}></Icon>
