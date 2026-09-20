<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yoo8g9amd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yoo8g9amd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:zoom-document-remix" {...props}></Icon>
