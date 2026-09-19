<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dx9tb8boy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="dx9tb8boy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:route-outline" {...props}></Icon>
