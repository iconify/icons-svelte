<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jnw1wt3zy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="jnw1wt3zy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:smiley-plus-bold" {...props}></Icon>
