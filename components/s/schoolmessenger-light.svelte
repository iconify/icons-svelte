<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ywnwpqb8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ywnwpqb8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:schoolmessenger-light" {...props}></Icon>
