<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c0h03dbrh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c0h03dbrh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:shield-checkmark" {...props}></Icon>
