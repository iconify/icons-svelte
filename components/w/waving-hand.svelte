<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7f-vm4dn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="g7f-vm4dn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:waving-hand" {...props}></Icon>
