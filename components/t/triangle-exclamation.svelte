<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rib8vw59i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rib8vw59i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:triangle-exclamation" {...props}></Icon>
