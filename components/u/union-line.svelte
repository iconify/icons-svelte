<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qc5zfuica.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qc5zfuica"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:union-line" {...props}></Icon>
