<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sui435b-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="sui435b-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:user-group" {...props}></Icon>
