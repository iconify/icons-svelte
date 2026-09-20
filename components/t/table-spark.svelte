<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyijvbab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cuyijvbab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:table-spark" {...props}></Icon>
