<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l4tspmkzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="l4tspmkzg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:squareh" {...props}></Icon>
