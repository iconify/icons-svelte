<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vhqgeeukd.css';
import '../../css/g/g97n7gbnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vhqgeeukd"/><path class="g97n7gbnl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:towel-filled" {...props}></Icon>
