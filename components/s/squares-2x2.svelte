<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zdgkpzv5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zdgkpzv5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:squares-2x2" {...props}></Icon>
