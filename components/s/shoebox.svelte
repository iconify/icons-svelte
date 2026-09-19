<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bey97dber.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":768};
const content = `<path class="bey97dber"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:shoebox" {...props}></Icon>
