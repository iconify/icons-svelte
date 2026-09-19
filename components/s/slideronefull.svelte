<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/co1d7b4qk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="co1d7b4qk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:slideronefull" {...props}></Icon>
