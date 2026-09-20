<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/imb743brv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="imb743brv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:windsurf-light" {...props}></Icon>
