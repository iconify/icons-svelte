<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z5rwa8b5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="z5rwa8b5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:user" {...props}></Icon>
