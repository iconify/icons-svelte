<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3cff8b-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c3cff8b-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:sofi" {...props}></Icon>
