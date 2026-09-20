<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ct3j1ul3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ct3j1ul3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:safe-2-outline" {...props}></Icon>
