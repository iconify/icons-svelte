<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/idf59lbkv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="idf59lbkv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:user-plus-corner-round" {...props}></Icon>
