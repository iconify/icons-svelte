<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y3q134bfl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="y3q134bfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:size" {...props}></Icon>
