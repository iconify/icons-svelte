<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b3gix-d_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b3gix-d_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:screenlite-dark" {...props}></Icon>
