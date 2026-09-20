<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/crovg-byq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="crovg-byq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:share-forward-fill" {...props}></Icon>
