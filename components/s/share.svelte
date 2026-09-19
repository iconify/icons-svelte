<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/us_d39b7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="us_d39b7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:share" {...props}></Icon>
