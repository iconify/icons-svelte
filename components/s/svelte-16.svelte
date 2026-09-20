<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c1qercc3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="c1qercc3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nonicons:svelte-16" {...props}></Icon>
