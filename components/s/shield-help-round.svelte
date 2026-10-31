<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ti0u3_bht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ti0u3_bht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:shield-help-round" {...props}></Icon>
