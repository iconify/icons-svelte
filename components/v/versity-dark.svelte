<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pjc0mib_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pjc0mib_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:versity-dark" {...props}></Icon>
