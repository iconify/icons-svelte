<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/suqnk2net.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="suqnk2net"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:terminalalt" {...props}></Icon>
