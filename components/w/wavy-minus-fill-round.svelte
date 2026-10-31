<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eaoiwm7ah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eaoiwm7ah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:wavy-minus-fill-round" {...props}></Icon>
