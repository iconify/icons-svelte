<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sio0q-bpj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sio0q-bpj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:shield-lock-open-outline" {...props}></Icon>
