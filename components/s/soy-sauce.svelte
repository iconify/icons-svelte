<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dqp026biz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dqp026biz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:soy-sauce" {...props}></Icon>
