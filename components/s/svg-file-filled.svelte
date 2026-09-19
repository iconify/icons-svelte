<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sh87aubun.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sh87aubun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:svg-file-filled" {...props}></Icon>
