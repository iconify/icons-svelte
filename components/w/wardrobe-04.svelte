<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q5np71b-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q5np71b-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:wardrobe-04" {...props}></Icon>
