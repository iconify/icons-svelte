<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g4dzq_bfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g4dzq_bfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:text-align-justify-fill" {...props}></Icon>
