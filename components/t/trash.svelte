<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ielc4mb8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ielc4mb8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:trash" {...props}></Icon>
