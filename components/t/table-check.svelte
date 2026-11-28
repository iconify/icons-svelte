<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3swr3b7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l3swr3b7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:table-check" {...props}></Icon>
