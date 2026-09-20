<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yq8hp2o_x.css';
import '../../css/o/o3ulf3bpl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yq8hp2o_x"/><path class="o3ulf3bpl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:wbtc" {...props}></Icon>
