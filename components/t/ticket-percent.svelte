<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oj12ojbci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oj12ojbci"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:ticket-percent" {...props}></Icon>
