<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/inzrwuhhf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="inzrwuhhf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rustdesk-dark" {...props}></Icon>
