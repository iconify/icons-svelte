<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/olsgmjbwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="olsgmjbwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:stamp" {...props}></Icon>
