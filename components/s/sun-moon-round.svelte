<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ualdwgz4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ualdwgz4h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:sun-moon-round" {...props}></Icon>
