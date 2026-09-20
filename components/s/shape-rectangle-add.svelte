<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_yym11fv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s_yym11fv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:shape-rectangle-add" {...props}></Icon>
