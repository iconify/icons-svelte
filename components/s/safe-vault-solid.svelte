<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yrl9mxa-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yrl9mxa-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:safe-vault-solid" {...props}></Icon>
