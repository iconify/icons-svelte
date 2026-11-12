<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o376dkb2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o376dkb2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:x-p-ferd" {...props}></Icon>
