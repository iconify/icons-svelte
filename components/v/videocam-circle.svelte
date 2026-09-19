<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-6w0qb7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="n-6w0qb7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:videocam-circle" {...props}></Icon>
