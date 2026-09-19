<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qc57nxbkk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qc57nxbkk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:tool-box" {...props}></Icon>
