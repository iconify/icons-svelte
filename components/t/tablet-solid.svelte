<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hmmn-vnbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hmmn-vnbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:tablet-solid" {...props}></Icon>
