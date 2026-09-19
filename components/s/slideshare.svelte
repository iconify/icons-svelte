<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/icdyelbac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1792};
const content = `<path class="icdyelbac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:slideshare" {...props}></Icon>
