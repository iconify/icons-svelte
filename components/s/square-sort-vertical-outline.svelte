<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ai1gpwbus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ai1gpwbus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:square-sort-vertical-outline" {...props}></Icon>
