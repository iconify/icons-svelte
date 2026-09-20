<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ll5fo4b3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ll5fo4b3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:smart-vacuum-cleaner-2-outline" {...props}></Icon>
