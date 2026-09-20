<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nfewxjb3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nfewxjb3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:user-circle-filled" {...props}></Icon>
