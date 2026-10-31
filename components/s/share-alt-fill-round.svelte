<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/av-fufpup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="av-fufpup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:share-alt-fill-round" {...props}></Icon>
