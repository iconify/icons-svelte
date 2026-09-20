<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yabvmqbqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":255};
const content = `<path class="yabvmqbqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:typesense" {...props}></Icon>
