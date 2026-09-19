<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ekgwi8jyj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ekgwi8jyj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:trophy" {...props}></Icon>
