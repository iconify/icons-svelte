<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x2zeo2byx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x2zeo2byx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:varicose-vein-24px" {...props}></Icon>
