<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gwk2vgbgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gwk2vgbgb primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:unfold-horizontal-duotone" {...props}></Icon>
