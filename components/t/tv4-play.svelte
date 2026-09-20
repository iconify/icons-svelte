<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sscfj9bpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sscfj9bpr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:tv4-play" {...props}></Icon>
