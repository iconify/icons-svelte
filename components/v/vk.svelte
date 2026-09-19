<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1dt9pesp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":640};
const content = `<path class="j1dt9pesp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:vk" {...props}></Icon>
