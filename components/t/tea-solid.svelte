<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/djl73n95t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="djl73n95t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:tea-solid" {...props}></Icon>
