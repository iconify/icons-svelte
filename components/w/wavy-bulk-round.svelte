<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/umqey9sxu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="umqey9sxu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:wavy-bulk-round" {...props}></Icon>
