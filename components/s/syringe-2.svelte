<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ddbtrpxcv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ddbtrpxcv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber:syringe-2" {...props}></Icon>
