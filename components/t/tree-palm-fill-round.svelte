<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uljkj_b_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uljkj_b_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:tree-palm-fill-round" {...props}></Icon>
