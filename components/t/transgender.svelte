<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wvithbb2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1408,"height":1792};
const content = `<path class="wvithbb2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:transgender" {...props}></Icon>
