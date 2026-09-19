<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/olt19cb-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="olt19cb-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:square-unlock-01" {...props}></Icon>
