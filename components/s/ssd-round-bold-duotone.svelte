<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6h73cb-x.css';
import '../../css/v/vpz4phbzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f6h73cb-x"/><path clip-rule="evenodd" class="vpz4phbzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:ssd-round-bold-duotone" {...props}></Icon>
