<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tt6ep9b-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tt6ep9b-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:share-2" {...props}></Icon>
