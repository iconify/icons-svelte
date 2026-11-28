<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-pmrsbag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v-pmrsbag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:settings-check" {...props}></Icon>
