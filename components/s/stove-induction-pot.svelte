<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vdvz_fe7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vdvz_fe7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:stove-induction-pot" {...props}></Icon>
