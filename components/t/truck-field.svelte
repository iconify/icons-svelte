<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kfaa8oorn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="kfaa8oorn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:truck-field" {...props}></Icon>
