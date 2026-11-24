<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nod_500mb.css';
import '../../css/q/qb37dcqql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nod_500mb"/><path class="qb37dcqql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:screen-share-filled" {...props}></Icon>
