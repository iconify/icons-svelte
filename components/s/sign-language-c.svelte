<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hdoy8tbjz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hdoy8tbjz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:sign-language-c" {...props}></Icon>
