<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xb9qe_c6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xb9qe_c6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:syllabary-katakana" {...props}></Icon>
