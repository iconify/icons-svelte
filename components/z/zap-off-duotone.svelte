<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/elhwibb4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="elhwibb4u primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:zap-off-duotone" {...props}></Icon>
