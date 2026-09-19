<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cqpsy4b5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cqpsy4b5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:terminal" {...props}></Icon>
