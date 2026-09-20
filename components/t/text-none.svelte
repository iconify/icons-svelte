<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_4amlb7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="f_4amlb7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:text-none" {...props}></Icon>
