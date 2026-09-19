<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oxuvarb9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oxuvarb9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:scan-search" {...props}></Icon>
