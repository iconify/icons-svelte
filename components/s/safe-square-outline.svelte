<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oi16cl6td.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oi16cl6td"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:safe-square-outline" {...props}></Icon>
