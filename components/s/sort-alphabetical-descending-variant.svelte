<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ttxsexshj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ttxsexshj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:sort-alphabetical-descending-variant" {...props}></Icon>
