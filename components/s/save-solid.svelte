<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b2z9d7bwa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b2z9d7bwa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:save-solid" {...props}></Icon>
