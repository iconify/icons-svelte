<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/imdnqvn5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="imdnqvn5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:stroke-width" {...props}></Icon>
