<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ovysgutzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ovysgutzl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:table-split-filled" {...props}></Icon>
