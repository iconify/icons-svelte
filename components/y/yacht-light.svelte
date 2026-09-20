<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fm-bt5bgf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fm-bt5bgf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:yacht-light" {...props}></Icon>
