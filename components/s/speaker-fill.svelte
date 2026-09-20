<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sku5yxboa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sku5yxboa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:speaker-fill" {...props}></Icon>
