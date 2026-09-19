<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w9f2nzuog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="w9f2nzuog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:square-reddit" {...props}></Icon>
