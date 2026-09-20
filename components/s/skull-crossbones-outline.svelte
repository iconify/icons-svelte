<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nt_lgabit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nt_lgabit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:skull-crossbones-outline" {...props}></Icon>
