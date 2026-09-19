<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nug-zsezx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1026};
const content = `<path class="nug-zsezx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:watermelon" {...props}></Icon>
