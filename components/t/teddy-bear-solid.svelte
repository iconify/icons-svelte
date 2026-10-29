<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/go8zk9zko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="go8zk9zko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:teddy-bear-solid" {...props}></Icon>
