<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gkilrjbpe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gkilrjbpe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:vagina-alt-outline-24px" {...props}></Icon>
