<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l68xvwp9a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l68xvwp9a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:traefik-dark" {...props}></Icon>
