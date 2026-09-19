<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mt0vp4b4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mt0vp4b4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:umbrella-filled" {...props}></Icon>
