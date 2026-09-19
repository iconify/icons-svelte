<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o7z5z-b0w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o7z5z-b0w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:toast-butter-filled" {...props}></Icon>
