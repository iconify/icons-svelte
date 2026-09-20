<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n7o570b7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n7o570b7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:share-forward-line" {...props}></Icon>
