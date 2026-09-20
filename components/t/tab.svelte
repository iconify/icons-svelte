<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-bib9iuo.css';
import '../../css/u/u2_or7bit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v-bib9iuo"/><path clip-rule="evenodd" class="u2_or7bit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:tab" {...props}></Icon>
