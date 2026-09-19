<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kfyu9-bes.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="kfyu9-bes"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:streetside-split-minimize" {...props}></Icon>
