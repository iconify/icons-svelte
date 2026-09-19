<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rhb5h3agu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="rhb5h3agu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:trophy-outline" {...props}></Icon>
