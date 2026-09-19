<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nzn2jab7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="nzn2jab7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:vault-wordmark" {...props}></Icon>
