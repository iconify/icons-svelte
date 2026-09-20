<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iqmq48xdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iqmq48xdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:vue-js-light" {...props}></Icon>
