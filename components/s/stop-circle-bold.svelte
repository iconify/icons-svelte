<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m65l5mb5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m65l5mb5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:stop-circle-bold" {...props}></Icon>
