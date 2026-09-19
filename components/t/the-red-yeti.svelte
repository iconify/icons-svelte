<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vx0k6uber.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="vx0k6uber"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:the-red-yeti" {...props}></Icon>
