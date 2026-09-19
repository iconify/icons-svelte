<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yuf4w3bjs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yuf4w3bjs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:shield-alert" {...props}></Icon>
