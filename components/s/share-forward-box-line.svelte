<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kxe83dlex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kxe83dlex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:share-forward-box-line" {...props}></Icon>
