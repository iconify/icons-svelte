<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ligmv2brr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ligmv2brr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:sort-ascending-shapes" {...props}></Icon>
