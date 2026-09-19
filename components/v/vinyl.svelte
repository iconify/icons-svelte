<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ehq2hbcmc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ehq2hbcmc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:vinyl" {...props}></Icon>
