<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bh3q-gbac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bh3q-gbac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:tactile-paving" {...props}></Icon>
