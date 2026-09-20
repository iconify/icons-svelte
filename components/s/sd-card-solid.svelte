<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w7vn98a0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="w7vn98a0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:sd-card-solid" {...props}></Icon>
