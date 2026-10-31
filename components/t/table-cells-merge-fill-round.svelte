<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r20pbs6eb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r20pbs6eb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:table-cells-merge-fill-round" {...props}></Icon>
