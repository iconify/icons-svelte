<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gd7evobee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gd7evobee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:text-wrap-column" {...props}></Icon>
