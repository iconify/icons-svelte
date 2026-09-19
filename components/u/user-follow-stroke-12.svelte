<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c6td3jbhf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="c6td3jbhf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:user-follow-stroke-12" {...props}></Icon>
