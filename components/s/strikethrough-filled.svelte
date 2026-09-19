<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nphfulbux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nphfulbux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:strikethrough-filled" {...props}></Icon>
