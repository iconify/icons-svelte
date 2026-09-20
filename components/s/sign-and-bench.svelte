<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nnp7o8bhw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="nnp7o8bhw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:sign-and-bench" {...props}></Icon>
