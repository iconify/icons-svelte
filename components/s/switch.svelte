<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/icw9h6w0k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="icw9h6w0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:switch" {...props}></Icon>
