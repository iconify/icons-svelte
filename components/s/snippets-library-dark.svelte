<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fa7tb9a1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fa7tb9a1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:snippets-library-dark" {...props}></Icon>
