<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v13-n1bhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v13-n1bhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:vlc-logo-block" {...props}></Icon>
