<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/suhmrh7ry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="suhmrh7ry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:shoko-server-light" {...props}></Icon>
