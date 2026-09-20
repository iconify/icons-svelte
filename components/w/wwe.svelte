<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vi-sd1bpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vi-sd1bpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:wwe" {...props}></Icon>
