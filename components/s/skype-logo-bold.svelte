<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vs0n-ypkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vs0n-ypkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:skype-logo-bold" {...props}></Icon>
