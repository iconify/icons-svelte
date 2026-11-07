<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m1dwv0bjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m1dwv0bjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:star-circle-outline" {...props}></Icon>
