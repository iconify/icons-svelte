<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pjdt1_b8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pjdt1_b8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:sort-desc" {...props}></Icon>
