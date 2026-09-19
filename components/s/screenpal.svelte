<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ef53n3xnu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="ef53n3xnu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:screenpal" {...props}></Icon>
