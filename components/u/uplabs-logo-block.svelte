<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yr1v6lfce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yr1v6lfce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:uplabs-logo-block" {...props}></Icon>
