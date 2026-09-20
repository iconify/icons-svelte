<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k9snh7bbb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="k9snh7bbb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:woy-marketplace" {...props}></Icon>
