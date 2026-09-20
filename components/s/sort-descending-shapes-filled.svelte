<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gy8w78pep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gy8w78pep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:sort-descending-shapes-filled" {...props}></Icon>
