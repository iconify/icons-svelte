<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pv17p37qt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pv17p37qt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:square-x" {...props}></Icon>
