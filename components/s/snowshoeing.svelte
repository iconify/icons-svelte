<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n2nhw313g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n2nhw313g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:snowshoeing" {...props}></Icon>
