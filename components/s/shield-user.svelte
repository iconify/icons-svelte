<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bv0ilfb2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="bv0ilfb2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:shield-user" {...props}></Icon>
