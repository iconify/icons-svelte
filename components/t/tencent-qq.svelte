<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ew3fm4blb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ew3fm4blb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:tencent-qq" {...props}></Icon>
