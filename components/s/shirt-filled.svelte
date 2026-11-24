<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wkgxcgqkf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wkgxcgqkf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:shirt-filled" {...props}></Icon>
