<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-6p3jmhi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1515,"height":912};
const content = `<path class="i-6p3jmhi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:vietnam-airlines" {...props}></Icon>
