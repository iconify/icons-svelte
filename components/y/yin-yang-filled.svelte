<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fw-cofgvd.css';
import '../../css/t/tngwchp1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fw-cofgvd"/><path class="tngwchp1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:yin-yang-filled" {...props}></Icon>
