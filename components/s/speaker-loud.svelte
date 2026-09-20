<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z578n6buf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="z578n6buf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:speaker-loud" {...props}></Icon>
