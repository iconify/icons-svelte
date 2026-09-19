<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/snv5e5f9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="snv5e5f9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:squarestar" {...props}></Icon>
