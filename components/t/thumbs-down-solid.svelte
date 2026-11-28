<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mfpk53bjw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mfpk53bjw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:thumbs-down-solid" {...props}></Icon>
