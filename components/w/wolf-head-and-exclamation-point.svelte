<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o81h3dbhb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="o81h3dbhb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:wolf-head-and-exclamation-point" {...props}></Icon>
