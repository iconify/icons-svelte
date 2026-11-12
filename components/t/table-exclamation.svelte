<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xj9b9rbwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xj9b9rbwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:table-exclamation" {...props}></Icon>
