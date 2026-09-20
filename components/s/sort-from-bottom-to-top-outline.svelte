<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x4fstvpbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x4fstvpbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:sort-from-bottom-to-top-outline" {...props}></Icon>
