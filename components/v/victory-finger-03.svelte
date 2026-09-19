<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ljx7t8mtz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ljx7t8mtz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:victory-finger-03" {...props}></Icon>
