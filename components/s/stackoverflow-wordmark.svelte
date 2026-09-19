<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uyh6tzb5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="uyh6tzb5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:stackoverflow-wordmark" {...props}></Icon>
