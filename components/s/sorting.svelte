<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lvw10qbnm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lvw10qbnm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:sorting" {...props}></Icon>
