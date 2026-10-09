<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sdkfekbin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="sdkfekbin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:swimming-20-bold" {...props}></Icon>
