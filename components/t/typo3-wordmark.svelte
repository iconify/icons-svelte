<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k1n-b7bkv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="k1n-b7bkv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:typo3-wordmark" {...props}></Icon>
