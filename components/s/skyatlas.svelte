<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wjrlzybmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":1280};
const content = `<path class="wjrlzybmw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:skyatlas" {...props}></Icon>
