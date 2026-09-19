<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rmzpx5bne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rmzpx5bne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:umbrella-outline" {...props}></Icon>
