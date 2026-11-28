<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ta7dw51we.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary ta7dw51we"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:zodiac-aquarius-duotone" {...props}></Icon>
