<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z1jehmq7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z1jehmq7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:text-italic-filled" {...props}></Icon>
