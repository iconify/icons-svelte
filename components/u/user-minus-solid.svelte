<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ivmqp4-dh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ivmqp4-dh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:user-minus-solid" {...props}></Icon>
