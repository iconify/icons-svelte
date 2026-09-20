<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sj7la-b6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sj7la-b6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:world-health-organization" {...props}></Icon>
