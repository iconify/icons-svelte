<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-n5_6z9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x-n5_6z9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:satellite" {...props}></Icon>
