<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3ks01b8e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":666,"height":680};
const content = `<path class="v3ks01b8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:stop" {...props}></Icon>
