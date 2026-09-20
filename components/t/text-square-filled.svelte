<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_wv7rbvb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p_wv7rbvb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:text-square-filled" {...props}></Icon>
