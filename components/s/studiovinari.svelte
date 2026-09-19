<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/scnep3brq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="scnep3brq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:studiovinari" {...props}></Icon>
