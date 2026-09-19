<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l0ory7bry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":680,"height":661};
const content = `<path class="l0ory7bry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:sitemap" {...props}></Icon>
