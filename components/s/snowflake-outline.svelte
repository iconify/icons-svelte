<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kjm6dccxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="kjm6dccxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:snowflake-outline" {...props}></Icon>
