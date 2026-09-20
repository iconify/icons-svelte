<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n2b4uobtl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n2b4uobtl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:text-x-square-filled" {...props}></Icon>
