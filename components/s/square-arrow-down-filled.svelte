<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/clrr77bhm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="clrr77bhm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-arrow-down-filled" {...props}></Icon>
