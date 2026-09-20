<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qzpqusz2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1534,"height":1225};
const content = `<path class="qzpqusz2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:sandisk" {...props}></Icon>
