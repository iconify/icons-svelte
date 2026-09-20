<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ycv1egpln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ycv1egpln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:text-cross-square-bold" {...props}></Icon>
