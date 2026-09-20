<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5i_igbuz.css';
import '../../css/l/ldw2udbvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w5i_igbuz"/><path class="ldw2udbvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:share-forward" {...props}></Icon>
