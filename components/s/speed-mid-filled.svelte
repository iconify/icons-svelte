<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cbkpzy2uz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cbkpzy2uz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:speed-mid-filled" {...props}></Icon>
