<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ez_ubmble.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ez_ubmble"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:wolfram-language" {...props}></Icon>
