<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w91s3cc_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="w91s3cc_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:six-minus" {...props}></Icon>
