<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vi7f8tu-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vi7f8tu-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:zip-file-solid" {...props}></Icon>
