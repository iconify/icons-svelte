<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tfuanbccs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":800,"height":405};
const content = `<path class="tfuanbccs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:xstate-light" {...props}></Icon>
