<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tp6t8obxz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tp6t8obxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:voicemail-fill-round" {...props}></Icon>
