<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w1jeki3de.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w1jeki3de"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:square-bar-chart-sharp-fill" {...props}></Icon>
