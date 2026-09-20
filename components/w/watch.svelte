<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/isdhl6lzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="isdhl6lzg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:watch" {...props}></Icon>
