<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pxom58b-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pxom58b-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:siren" {...props}></Icon>
