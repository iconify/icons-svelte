<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xrv6k5hte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xrv6k5hte"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:sifive" {...props}></Icon>
