<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft08bqkvi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ft08bqkvi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:youtube" {...props}></Icon>
