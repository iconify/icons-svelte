<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ks_7h928z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ks_7h928z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:wrench-16-solid" {...props}></Icon>
