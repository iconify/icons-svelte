<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uvf88-v-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="uvf88-v-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:trash2" {...props}></Icon>
