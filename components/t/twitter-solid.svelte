<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k5e7095cp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="k5e7095cp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:twitter-solid" {...props}></Icon>
