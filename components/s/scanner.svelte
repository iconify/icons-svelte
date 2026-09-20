<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wj5_9902t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wj5_9902t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:scanner" {...props}></Icon>
