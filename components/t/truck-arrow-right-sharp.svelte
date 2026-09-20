<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/arh7qe-ge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="arh7qe-ge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:truck-arrow-right-sharp" {...props}></Icon>
