<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v72m8yb1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v72m8yb1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:table-2-line" {...props}></Icon>
