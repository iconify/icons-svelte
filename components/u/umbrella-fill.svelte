<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gcm29cc_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gcm29cc_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:umbrella-fill" {...props}></Icon>
