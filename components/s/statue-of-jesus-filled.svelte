<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v44b4xb9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v44b4xb9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:statue-of-jesus-filled" {...props}></Icon>
