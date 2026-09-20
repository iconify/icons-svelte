<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w24y-uupq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w24y-uupq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:sun-set-fill" {...props}></Icon>
