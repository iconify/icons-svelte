<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wllv4abeh.css';
import '../../css/u/ui1cszbdy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wllv4abeh"/><path class="ui1cszbdy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:telephone-1" {...props}></Icon>
