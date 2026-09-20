<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v2q5edc7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v2q5edc7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-toggle-horizontal" {...props}></Icon>
