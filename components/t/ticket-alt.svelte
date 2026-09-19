<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kricpd2si.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="kricpd2si"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:ticket-alt" {...props}></Icon>
