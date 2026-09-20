<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/np6v3sb1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="np6v3sb1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:tag-connection-view" {...props}></Icon>
