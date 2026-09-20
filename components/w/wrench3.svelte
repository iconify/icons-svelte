<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-h28mb2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="x-h28mb2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:wrench3" {...props}></Icon>
