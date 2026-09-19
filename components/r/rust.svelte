<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nc7hqw7to.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nc7hqw7to"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:rust" {...props}></Icon>
