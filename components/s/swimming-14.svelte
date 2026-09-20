<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wt4v5ebog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="wt4v5ebog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:swimming-14" {...props}></Icon>
