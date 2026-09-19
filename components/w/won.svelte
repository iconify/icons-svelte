<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xgx4fhnss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1408};
const content = `<path class="xgx4fhnss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:won" {...props}></Icon>
