<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gu0vqebuc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gu0vqebuc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:script" {...props}></Icon>
