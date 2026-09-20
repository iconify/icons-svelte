<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k9kgs3l3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k9kgs3l3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:sliders-vertical-fill" {...props}></Icon>
