<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e75k15bbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e75k15bbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:server-outline" {...props}></Icon>
