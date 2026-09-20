<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u4nltkd0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u4nltkd0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:sd-card-outline" {...props}></Icon>
