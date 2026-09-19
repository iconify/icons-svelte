<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/za7fcp6wb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="za7fcp6wb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:targeted" {...props}></Icon>
