<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jdjwg0wvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jdjwg0wvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:wikivoyage" {...props}></Icon>
