<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cxk6u5upa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cxk6u5upa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:upload-computer-solid" {...props}></Icon>
