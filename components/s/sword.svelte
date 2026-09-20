<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fa1hmy53v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="fa1hmy53v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:sword" {...props}></Icon>
