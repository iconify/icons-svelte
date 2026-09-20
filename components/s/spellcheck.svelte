<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ouc14g95t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ouc14g95t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:spellcheck" {...props}></Icon>
