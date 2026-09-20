<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xfm-5fbma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xfm-5fbma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:user-protection-1-solid" {...props}></Icon>
