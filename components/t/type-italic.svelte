<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gpi10xpow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gpi10xpow"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:type-italic" {...props}></Icon>
