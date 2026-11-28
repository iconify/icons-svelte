<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hykce9b8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="hykce9b8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:shield-user-light" {...props}></Icon>
