<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/poyhed4yu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="poyhed4yu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:share-3-line" {...props}></Icon>
