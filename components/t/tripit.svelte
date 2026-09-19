<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q8qzr6bvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":464,"height":448};
const content = `<path class="q8qzr6bvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:tripit" {...props}></Icon>
