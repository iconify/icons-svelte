<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eyu8vtd1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eyu8vtd1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:search-check-solid" {...props}></Icon>
