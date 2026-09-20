<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dmm_ovqpx.css';
import '../../css/b/bem6xnbwz.css';
import '../../css/y/yx9j9-c-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dmm_ovqpx"/><path clip-rule="evenodd" class="bem6xnbwz"/><path class="yx9j9-c-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:sort-by-alphabet-bold-duotone" {...props}></Icon>
