<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w8dtt-bni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w8dtt-bni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:sort-asc-filled" {...props}></Icon>
