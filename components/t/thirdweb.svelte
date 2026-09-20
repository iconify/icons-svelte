<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fyoaf3pwo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fyoaf3pwo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:thirdweb" {...props}></Icon>
