<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/if3b41utp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="if3b41utp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:subtract" {...props}></Icon>
