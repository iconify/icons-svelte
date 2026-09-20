<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/asf4shgzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="asf4shgzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:snowboarding-solid" {...props}></Icon>
