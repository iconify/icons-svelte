<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/blgxw44em.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="blgxw44em"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:table-2" {...props}></Icon>
