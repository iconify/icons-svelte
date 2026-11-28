<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uzzepkb5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="uzzepkb5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:sidebar-simple-close-thin" {...props}></Icon>
