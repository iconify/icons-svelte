<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/amqcs7bcf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="amqcs7bcf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:yahoo2" {...props}></Icon>
