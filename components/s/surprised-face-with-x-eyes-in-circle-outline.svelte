<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bzdcx9bzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="bzdcx9bzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:surprised-face-with-x-eyes-in-circle-outline" {...props}></Icon>
