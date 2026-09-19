<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sufpb4bjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sufpb4bjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:screen-full-fill" {...props}></Icon>
