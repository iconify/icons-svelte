<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zhhvqwbng.css';
import '../../css/e/era03mble.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zhhvqwbng"/><path class="era03mble"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:scroll-48-bold" {...props}></Icon>
