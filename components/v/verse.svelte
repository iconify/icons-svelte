<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v2_jdtb8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v2_jdtb8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:verse" {...props}></Icon>
