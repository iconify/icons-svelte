<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s5e0lmnbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s5e0lmnbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tvdb-dark" {...props}></Icon>
