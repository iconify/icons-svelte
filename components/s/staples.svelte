<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g8ul-wbxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":184.201,"height":38.9};
const content = `<path class="g8ul-wbxh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:staples" {...props}></Icon>
