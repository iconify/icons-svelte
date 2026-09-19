<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lj4cr7bwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lj4cr7bwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:scissors" {...props}></Icon>
