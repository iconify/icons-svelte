<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ru30nfcqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ru30nfcqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:section-fill" {...props}></Icon>
