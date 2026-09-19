<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-fl9tbbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="t-fl9tbbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:user-favorite-alt" {...props}></Icon>
