<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bzyd7bckj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="bzyd7bckj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:wrench" {...props}></Icon>
