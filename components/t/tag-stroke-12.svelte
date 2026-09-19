<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n5bbp6dej.css';
import '../../css/e/e7ba03bxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="n5bbp6dej"/><circle class="e7ba03bxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:tag-stroke-12" {...props}></Icon>
