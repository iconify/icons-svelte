<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bsu03k0ky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="bsu03k0ky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:sparkles-16-solid" {...props}></Icon>
