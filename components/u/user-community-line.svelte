<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/su65qprpo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="su65qprpo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:user-community-line" {...props}></Icon>
