<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_8ewqxve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z_8ewqxve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:streaming-logo-block" {...props}></Icon>
