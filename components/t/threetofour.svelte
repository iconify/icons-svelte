<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pufi5ikpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":768};
const content = `<path class="pufi5ikpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:threetofour" {...props}></Icon>
