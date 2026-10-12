<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lk2pvgbtx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lk2pvgbtx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:user-plus-filled" {...props}></Icon>
