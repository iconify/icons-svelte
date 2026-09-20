<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yxxj42bxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="yxxj42bxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:social-dribbble" {...props}></Icon>
