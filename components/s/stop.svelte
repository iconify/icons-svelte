<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p9i2nublj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="p9i2nublj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:stop" {...props}></Icon>
