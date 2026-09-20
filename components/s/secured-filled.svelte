<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_pg77bup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p_pg77bup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:secured-filled" {...props}></Icon>
