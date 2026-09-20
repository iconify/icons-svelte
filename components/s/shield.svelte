<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rh14myekq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="rh14myekq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:shield" {...props}></Icon>
