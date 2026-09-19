<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9pvjwbtk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1026};
const content = `<path class="r9pvjwbtk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:textlayer" {...props}></Icon>
