<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cdh1b5bwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cdh1b5bwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:text-square-bold" {...props}></Icon>
