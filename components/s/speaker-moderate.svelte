<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/byy98xbhl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="byy98xbhl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:speaker-moderate" {...props}></Icon>
