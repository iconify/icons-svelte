<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e8y-w-skm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e8y-w-skm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:share-03" {...props}></Icon>
