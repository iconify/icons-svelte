<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y5re3sbmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y5re3sbmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:wolf-pack-battalion" {...props}></Icon>
