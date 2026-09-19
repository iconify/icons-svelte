<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hkf1x5yse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="hkf1x5yse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:smoking-symbol" {...props}></Icon>
