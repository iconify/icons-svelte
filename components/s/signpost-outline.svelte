<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u8b1vfbix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u8b1vfbix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:signpost-outline" {...props}></Icon>
