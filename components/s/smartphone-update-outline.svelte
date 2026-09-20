<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_8sl_z9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q_8sl_z9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:smartphone-update-outline" {...props}></Icon>
