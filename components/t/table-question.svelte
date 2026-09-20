<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/auyq2-22y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="auyq2-22y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:table-question" {...props}></Icon>
