<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fgt1bzbta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fgt1bzbta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:trillertv" {...props}></Icon>
