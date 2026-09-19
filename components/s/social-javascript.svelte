<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yk-cdeb0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yk-cdeb0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:social-javascript" {...props}></Icon>
