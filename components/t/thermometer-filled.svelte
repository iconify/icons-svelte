<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qwpu5t_vw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qwpu5t_vw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:thermometer-filled" {...props}></Icon>
