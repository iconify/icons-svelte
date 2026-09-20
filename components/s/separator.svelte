<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ys9-2ab3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="ys9-2ab3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:separator" {...props}></Icon>
