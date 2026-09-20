<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/encmt3bah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="encmt3bah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:tshirt" {...props}></Icon>
