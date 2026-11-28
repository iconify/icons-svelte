<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uqjozml0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="uqjozml0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:sidebar-simple-right-thin" {...props}></Icon>
