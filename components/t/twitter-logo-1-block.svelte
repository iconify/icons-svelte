<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cnm9e3w-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cnm9e3w-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:twitter-logo-1-block" {...props}></Icon>
