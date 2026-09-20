<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-v3g4bxu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e-v3g4bxu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:server-square-outline" {...props}></Icon>
