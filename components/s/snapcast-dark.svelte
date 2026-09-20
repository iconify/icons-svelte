<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gkwrstbqm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gkwrstbqm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:snapcast-dark" {...props}></Icon>
