<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d1kbnlx2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d1kbnlx2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:shield-gear" {...props}></Icon>
