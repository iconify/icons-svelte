<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tzo26gbnm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tzo26gbnm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:smartwatch" {...props}></Icon>
