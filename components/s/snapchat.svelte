<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lkrlu3b7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lkrlu3b7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:snapchat" {...props}></Icon>
