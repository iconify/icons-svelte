<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a8ylr-b4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a8ylr-b4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:vaccine" {...props}></Icon>
