<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kby68xphz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="kby68xphz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:svgo-wordmark" {...props}></Icon>
