<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x37too4bn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x37too4bn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:video" {...props}></Icon>
