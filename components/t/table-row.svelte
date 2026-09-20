<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wzddhlb3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wzddhlb3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:table-row" {...props}></Icon>
