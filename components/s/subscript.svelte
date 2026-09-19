<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b1lw2cc6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="b1lw2cc6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:subscript" {...props}></Icon>
