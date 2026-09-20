<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e6m1qpb2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e6m1qpb2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:star-circle" {...props}></Icon>
