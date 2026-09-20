<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dhb07vwbb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dhb07vwbb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:v-kontakte-logo-block" {...props}></Icon>
