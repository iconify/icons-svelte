<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tm3h5jbhj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="tm3h5jbhj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:social-twitter" {...props}></Icon>
