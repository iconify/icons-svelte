<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qe8i44bza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qe8i44bza"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:zend" {...props}></Icon>
