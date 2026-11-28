<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qoqb84bux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qoqb84bux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:wifi-low-solid" {...props}></Icon>
