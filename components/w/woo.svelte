<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rxx2spbel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rxx2spbel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:woo" {...props}></Icon>
