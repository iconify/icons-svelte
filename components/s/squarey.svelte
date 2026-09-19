<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uy6mme2wu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="uy6mme2wu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:squarey" {...props}></Icon>
