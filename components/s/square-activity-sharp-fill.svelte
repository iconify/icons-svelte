<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m94-e1boj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m94-e1boj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:square-activity-sharp-fill" {...props}></Icon>
