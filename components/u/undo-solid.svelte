<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ij0gr3wtk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ij0gr3wtk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:undo-solid" {...props}></Icon>
