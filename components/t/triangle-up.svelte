<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rtjok5b9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="rtjok5b9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:triangle-up" {...props}></Icon>
