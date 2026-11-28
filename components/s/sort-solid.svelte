<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qj2o055wt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qj2o055wt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:sort-solid" {...props}></Icon>
