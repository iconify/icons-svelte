<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pu5troc5n.css';
import '../../css/u/unhe2tbbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pu5troc5n"/><path class="unhe2tbbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:ultra" {...props}></Icon>
