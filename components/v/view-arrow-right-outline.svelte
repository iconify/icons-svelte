<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dqc5o4bpj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dqc5o4bpj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:view-arrow-right-outline" {...props}></Icon>
