<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qeuowkzon.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qeuowkzon"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:sortifyr-dark" {...props}></Icon>
