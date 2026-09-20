<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kqz78abfb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kqz78abfb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:vox" {...props}></Icon>
