<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ope5wjb1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ope5wjb1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:sorting-az-01" {...props}></Icon>
