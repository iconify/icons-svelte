<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/orkbj-bkf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="orkbj-bkf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:soundwave-square-outline" {...props}></Icon>
