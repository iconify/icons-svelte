<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/apie_-4pn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="apie_-4pn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:type-h3" {...props}></Icon>
