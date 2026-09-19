<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sfqf04b7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1280,"height":1408};
const content = `<path class="sfqf04b7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:ruble" {...props}></Icon>
