<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ni3qxcbkc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ni3qxcbkc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:train-lightrail-front-fill" {...props}></Icon>
