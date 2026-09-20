<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/plytxvb-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="plytxvb-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:sum" {...props}></Icon>
