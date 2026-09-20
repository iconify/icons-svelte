<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2r4mmblp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":134,"height":135};
const content = `<path clip-rule="evenodd" class="k2r4mmblp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:xata" {...props}></Icon>
