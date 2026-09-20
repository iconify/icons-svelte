<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bl0-71bkm.css';
import '../../css/s/s7e79xbzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bl0-71bkm"/><path class="s7e79xbzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:upload-brackets-bold" {...props}></Icon>
