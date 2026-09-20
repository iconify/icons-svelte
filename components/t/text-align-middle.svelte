<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mmqnm6b4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="mmqnm6b4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:text-align-middle" {...props}></Icon>
