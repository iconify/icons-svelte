<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xm0unvb9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xm0unvb9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:youtube" {...props}></Icon>
