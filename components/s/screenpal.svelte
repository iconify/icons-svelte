<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rmuw75duc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rmuw75duc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:screenpal" {...props}></Icon>
