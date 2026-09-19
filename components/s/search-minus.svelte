<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uff8yccku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1664,"height":1664};
const content = `<path class="uff8yccku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:search-minus" {...props}></Icon>
