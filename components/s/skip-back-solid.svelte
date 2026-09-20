<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l9vw5s0cw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l9vw5s0cw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:skip-back-solid" {...props}></Icon>
