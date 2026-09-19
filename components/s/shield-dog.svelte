<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/km78v5cyw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="km78v5cyw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:shield-dog" {...props}></Icon>
