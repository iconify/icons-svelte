<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v440o84zi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v440o84zi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:user-round-star" {...props}></Icon>
