<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u6mw1bpfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u6mw1bpfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:text-italic-circle-bold" {...props}></Icon>
