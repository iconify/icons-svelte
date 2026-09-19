<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c32_mab1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="c32_mab1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:subdomain" {...props}></Icon>
