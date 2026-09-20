<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uw6v8tb9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uw6v8tb9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:user-code" {...props}></Icon>
