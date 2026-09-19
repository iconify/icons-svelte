<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bsfw2vjvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bsfw2vjvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:visa" {...props}></Icon>
