<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tnxue8ken.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tnxue8ken"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:upload-square2-filled" {...props}></Icon>
