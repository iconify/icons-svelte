<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wdk78rbzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1000,"height":1000};
const content = `<path class="wdk78rbzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="brandico:visa" {...props}></Icon>
