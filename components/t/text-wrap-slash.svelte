<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p9qxjwb6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="p9qxjwb6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:text-wrap-slash" {...props}></Icon>
