<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ig8s2roze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="ig8s2roze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:underline-20-solid" {...props}></Icon>
