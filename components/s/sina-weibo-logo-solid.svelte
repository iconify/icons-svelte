<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/smpw6-uka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="smpw6-uka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:sina-weibo-logo-solid" {...props}></Icon>
