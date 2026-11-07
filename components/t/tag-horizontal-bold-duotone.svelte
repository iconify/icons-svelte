<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/opx7yx7he.css';
import '../../css/e/ecc5nebhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="opx7yx7he"/><path class="ecc5nebhy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:tag-horizontal-bold-duotone" {...props}></Icon>
