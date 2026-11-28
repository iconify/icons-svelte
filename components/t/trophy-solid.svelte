<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qguc40bkq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qguc40bkq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:trophy-solid" {...props}></Icon>
