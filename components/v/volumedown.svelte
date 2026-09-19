<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l4gk5-dnq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":13};
const content = `<path class="l4gk5-dnq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:volumedown" {...props}></Icon>
