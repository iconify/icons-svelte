<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zgm--ccyb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zgm--ccyb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:triangle-filled" {...props}></Icon>
