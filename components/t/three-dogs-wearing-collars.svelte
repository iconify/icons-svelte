<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gb9hgyngx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gb9hgyngx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:three-dogs-wearing-collars" {...props}></Icon>
