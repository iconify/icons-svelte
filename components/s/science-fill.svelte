<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/piy1tubod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="piy1tubod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:science-fill" {...props}></Icon>
