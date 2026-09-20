<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t8h8q4bhj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t8h8q4bhj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-chevrons-right-filled" {...props}></Icon>
