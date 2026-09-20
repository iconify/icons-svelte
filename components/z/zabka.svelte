<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/emx2i_-og.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="emx2i_-og"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:zabka" {...props}></Icon>
