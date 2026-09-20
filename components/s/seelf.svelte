<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jjyyrubdb.css';
import '../../css/l/l0tnl8bcg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jjyyrubdb"/><path class="l0tnl8bcg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:seelf" {...props}></Icon>
