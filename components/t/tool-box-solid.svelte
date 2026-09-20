<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d516btmhw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d516btmhw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:tool-box-solid" {...props}></Icon>
