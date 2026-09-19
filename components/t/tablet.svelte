<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fmap0gbol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1152,"height":1408};
const content = `<path class="fmap0gbol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:tablet" {...props}></Icon>
