<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pveucb2ak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pveucb2ak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:voicemail" {...props}></Icon>
