<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w6syj0blk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="w6syj0blk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:social-spotify" {...props}></Icon>
