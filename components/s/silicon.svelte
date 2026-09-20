<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xl3zvd-ae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xl3zvd-ae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:silicon" {...props}></Icon>
