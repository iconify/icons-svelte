<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ocbd0c1lk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ocbd0c1lk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:view-split-20-solid" {...props}></Icon>
