<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x7q42soot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="x7q42soot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:squarez" {...props}></Icon>
