<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tznw7je4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="tznw7je4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:text-align-center" {...props}></Icon>
