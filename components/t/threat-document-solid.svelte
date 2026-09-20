<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zn6f7hbhs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="zn6f7hbhs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:threat-document-solid" {...props}></Icon>
