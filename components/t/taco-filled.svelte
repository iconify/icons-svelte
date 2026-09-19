<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uya9hk5sf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uya9hk5sf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:taco-filled" {...props}></Icon>
