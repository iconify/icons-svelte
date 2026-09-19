<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dqfn-ipyo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1158.764,"height":1000};
const content = `<path class="dqfn-ipyo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="brandico:vimeo" {...props}></Icon>
