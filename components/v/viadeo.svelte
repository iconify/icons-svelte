<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hey2x6psv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1280,"height":1536};
const content = `<path class="hey2x6psv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:viadeo" {...props}></Icon>
