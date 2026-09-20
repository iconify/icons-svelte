<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x98hq1byo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x98hq1byo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:test" {...props}></Icon>
