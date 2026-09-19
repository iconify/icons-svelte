<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/avjkpk4pv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="avjkpk4pv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:snail" {...props}></Icon>
