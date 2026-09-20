<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zm2fwabtn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="zm2fwabtn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:vector-document-outline" {...props}></Icon>
