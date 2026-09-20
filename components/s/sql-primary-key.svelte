<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xygd24b4q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xygd24b4q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:sql-primary-key" {...props}></Icon>
