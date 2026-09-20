<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nco9tjboe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nco9tjboe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:whitesource-logo-2" {...props}></Icon>
