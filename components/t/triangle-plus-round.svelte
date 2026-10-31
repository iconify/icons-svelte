<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vszk6kbjw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vszk6kbjw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:triangle-plus-round" {...props}></Icon>
