<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4zj8ukpc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="k4zj8ukpc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:snooze" {...props}></Icon>
