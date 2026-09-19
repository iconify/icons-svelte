<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wppiylbfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":666,"height":680};
const content = `<path class="wppiylbfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:tumblr" {...props}></Icon>
