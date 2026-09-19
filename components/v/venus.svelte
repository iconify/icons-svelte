<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v7gofpb_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v7gofpb_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:venus" {...props}></Icon>
