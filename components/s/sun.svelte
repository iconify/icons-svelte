<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b9iraftnq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="b9iraftnq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:sun" {...props}></Icon>
