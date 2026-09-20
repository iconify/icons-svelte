<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b6ur09q4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b6ur09q4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:vbulletin" {...props}></Icon>
