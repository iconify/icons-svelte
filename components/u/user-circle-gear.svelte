<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pp40cv00c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pp40cv00c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:user-circle-gear" {...props}></Icon>
