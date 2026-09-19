<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f1ind-bsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":464,"height":488};
const content = `<path class="f1ind-bsz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:sharethis" {...props}></Icon>
