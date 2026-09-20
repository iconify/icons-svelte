<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bqp4w6tpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bqp4w6tpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:scalar" {...props}></Icon>
