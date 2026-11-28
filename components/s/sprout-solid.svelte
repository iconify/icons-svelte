<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d97_1ubgh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d97_1ubgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:sprout-solid" {...props}></Icon>
