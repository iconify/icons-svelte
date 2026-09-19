<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gvwio-8xu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":645,"height":751};
const content = `<path class="gvwio-8xu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:yelp" {...props}></Icon>
