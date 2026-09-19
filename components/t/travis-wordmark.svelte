<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iqgc4ybaj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="iqgc4ybaj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:travis-wordmark" {...props}></Icon>
