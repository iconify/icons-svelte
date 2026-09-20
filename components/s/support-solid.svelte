<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rj4ar5bfl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rj4ar5bfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:support-solid" {...props}></Icon>
