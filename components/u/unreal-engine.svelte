<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kcvz5dbex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kcvz5dbex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:unreal-engine" {...props}></Icon>
