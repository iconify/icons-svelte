<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cg4uccb5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="cg4uccb5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:turnstile" {...props}></Icon>
