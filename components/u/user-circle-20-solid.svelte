<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2hq26fol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="m2hq26fol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:user-circle-20-solid" {...props}></Icon>
