<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bo6_k6b5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="bo6_k6b5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:vapor-wordmark" {...props}></Icon>
