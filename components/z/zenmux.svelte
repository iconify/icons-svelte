<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wywyoxx-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wywyoxx-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:zenmux" {...props}></Icon>
