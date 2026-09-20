<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zsei18buf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zsei18buf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:share-2-fill" {...props}></Icon>
