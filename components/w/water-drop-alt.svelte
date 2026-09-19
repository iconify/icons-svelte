<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bntn4zffv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bntn4zffv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:water-drop-alt" {...props}></Icon>
