<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sdne1qt2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sdne1qt2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:wrench" {...props}></Icon>
