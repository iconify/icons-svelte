<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/csd2fybuj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="csd2fybuj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:user-nurse" {...props}></Icon>
