<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/igjfcmbmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="igjfcmbmb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:signal-full-remix" {...props}></Icon>
