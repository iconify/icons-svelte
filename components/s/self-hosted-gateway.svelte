<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bdgy03bmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bdgy03bmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:self-hosted-gateway" {...props}></Icon>
