<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/db8-kccpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="db8-kccpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:star-minus" {...props}></Icon>
