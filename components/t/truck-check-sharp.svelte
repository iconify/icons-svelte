<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k84s8obrr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k84s8obrr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:truck-check-sharp" {...props}></Icon>
