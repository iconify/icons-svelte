<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p8lu4nblm.css';
import '../../css/c/c21u_2--p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="p8lu4nblm"/><path class="c21u_2--p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:volume-unmuted-fill-12" {...props}></Icon>
