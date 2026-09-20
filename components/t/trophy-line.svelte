<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gjy069u9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gjy069u9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:trophy-line" {...props}></Icon>
