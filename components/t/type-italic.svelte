<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nqop9mawr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nqop9mawr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:type-italic" {...props}></Icon>
