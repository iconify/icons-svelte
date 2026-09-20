<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qjz9jgbbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qjz9jgbbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:wallet" {...props}></Icon>
