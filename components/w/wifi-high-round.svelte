<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/smw7abbpj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="smw7abbpj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:wifi-high-round" {...props}></Icon>
