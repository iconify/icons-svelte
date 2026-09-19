<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p1rz7qbma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="p1rz7qbma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:user-access-unlocked" {...props}></Icon>
