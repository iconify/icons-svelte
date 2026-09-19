<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tukxr95ba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tukxr95ba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:star" {...props}></Icon>
