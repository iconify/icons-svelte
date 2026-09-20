<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lilqhibhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="lilqhibhg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:taxi-under-key" {...props}></Icon>
