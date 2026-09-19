<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/du0059b8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="du0059b8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:rss" {...props}></Icon>
