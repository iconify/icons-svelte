<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/ways3sbhj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1025};
const content = `<path class="ways3sbhj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:twofingerswipeup" {...props}></Icon>
