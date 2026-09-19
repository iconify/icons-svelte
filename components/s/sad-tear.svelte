<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ke7kvacnq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="ke7kvacnq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:sad-tear" {...props}></Icon>
