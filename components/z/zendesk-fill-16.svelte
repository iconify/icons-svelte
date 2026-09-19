<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hscj6zgex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hscj6zgex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:zendesk-fill-16" {...props}></Icon>
