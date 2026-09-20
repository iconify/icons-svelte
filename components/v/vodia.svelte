<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-_jqacwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k-_jqacwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:vodia" {...props}></Icon>
