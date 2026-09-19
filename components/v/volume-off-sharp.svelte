<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/apsjy4boa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="apsjy4boa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:volume-off-sharp" {...props}></Icon>
