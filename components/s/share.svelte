<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_4dfqpjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="y_4dfqpjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:share" {...props}></Icon>
