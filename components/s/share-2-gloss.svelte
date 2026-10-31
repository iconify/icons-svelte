<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qr9y3zfcj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qr9y3zfcj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:share-2-gloss" {...props}></Icon>
