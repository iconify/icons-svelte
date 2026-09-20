<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gpl-qk7xb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gpl-qk7xb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:wifi" {...props}></Icon>
