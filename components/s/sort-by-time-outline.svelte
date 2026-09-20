<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ehw2eab2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ehw2eab2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:sort-by-time-outline" {...props}></Icon>
