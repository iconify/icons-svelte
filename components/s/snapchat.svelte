<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zfutznb8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zfutznb8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:snapchat" {...props}></Icon>
