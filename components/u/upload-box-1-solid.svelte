<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_3nmhnxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="i_3nmhnxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:upload-box-1-solid" {...props}></Icon>
