<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sm0jzlblr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="sm0jzlblr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:underline" {...props}></Icon>
