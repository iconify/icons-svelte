<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j9p79zvwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="j9p79zvwr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:speedometer" {...props}></Icon>
