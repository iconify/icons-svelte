<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mt35k1b6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mt35k1b6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:yui" {...props}></Icon>
