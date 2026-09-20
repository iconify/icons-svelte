<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q3pph2_eh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="q3pph2_eh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:ws-essentials" {...props}></Icon>
