<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ifjoykyat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="ifjoykyat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:squaretwo" {...props}></Icon>
