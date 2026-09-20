<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dmqrylq4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dmqrylq4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:shield-ban" {...props}></Icon>
