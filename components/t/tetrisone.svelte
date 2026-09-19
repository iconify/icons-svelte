<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mc8va39jk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":704,"height":1024};
const content = `<path class="mc8va39jk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:tetrisone" {...props}></Icon>
