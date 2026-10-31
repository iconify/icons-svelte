<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ed-kn0bym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ed-kn0bym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:shield-minus-fill-round" {...props}></Icon>
