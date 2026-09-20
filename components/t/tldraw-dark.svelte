<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b7i7nxq4v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b7i7nxq4v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tldraw-dark" {...props}></Icon>
